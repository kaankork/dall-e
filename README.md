# DALL·E: Creating Images from Text
This repo serves the purpose of experimenting [DALL·E: Creating Images from Text](https://openai.com/blog/dall-e/), published by OpenAI. 
Paper: https://arxiv.org/pdf/2102.12092.pdf

## Technical Features
- 12-billion parameter version of GPT-3 trained to generate images from text descriptions.
- It receives both the text and the image as a single stream of data containing up to 1280 tokens, and is trained using maximum likelihood to generate all of the tokens, one after another. This training procedure allows DALL·E to not only generate an image from scratch, but also to regenerate any rectangular region of an existing image that extends to the bottom-right corner, in a way that is consistent with the text prompt.

## Capabilities
- Controlling Attributes _(pentagonal green clock)_
- Drawing Multiple Objects _(a small red block sitting on a large green block)_
- Visualizing Perspective and Three-Dimensionality _(capybara made of voxels sitting in a field)_
- Visualizing Internal and External Structure _(a cross-section view of a walnut)_
- Inferring Contextual Details _(a painting of a capybara sitting in a field at sunrise)_
- Applications of Preceding Capabilities _(a male mannequin dressed in an orange and black flannel shirt)_
- Combining Unrelated Concepts (_an armchair in the shape of an avocado. an armchair imitating an avocado.)_
- Animal Illustrations _(an illustration of a baby daikon radish in a tutu walking a dog)_
- Zero-Shot Visual Reasoning _(the exact same teapot on the top with ’gpt’ written on it on the bottom)_
- Geographic Knowledge _(a photo of san francisco’s golden gate bridge)_
- Temporal Knowledge _(a photo pf a phone from the 20s)_


## Test Cases
- [ ] Half of a portrait to test how it generates the other half of the image - politicians? Marvel characters? 
