# Ideas
Content ideas

## NLP

### Text Classification

#### 1. Categorize Github Issues

Keeping the issue tracker tidy is something many open source projects struggle with – so automated tools could definitely be helpful. How easy would it be to create a bot to tag the issues automatically? Text classification really shines when the task would otherwise be performed by hand.

![Github issues](./img/issues.jpg)

- Training data: Easy to collect labeled data from existing Github issues (example: [spaCy issues](https://github.com/explosion/spaCy/issues))
  - Top Github projects with labels:
    - [GoLang](https://github.com/npm/npm/issues)
    - [FontAwesome](https://github.com/FortAwesome/Font-Awesome/issues)
    - [npm](https://github.com/npm/npm/issues)
    - More at [Octoverse](https://octoverse.github.com/)
  - Label categories: [https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/)
- Model: 
  - fastText: [https://github.com/facebookresearch/fastText](https://github.com/facebookresearch/fastText)
  - Comparison of different models: [https://github.com/brightmart/text_classification](https://github.com/brightmart/text_classification)
- Idea source: https://explosion.ai/blog/prodigy-annotation-tool-active-learning

----

### Reading

- [Applying deep learning to real-world problems](https://medium.com/merantix/applying-deep-learning-to-real-world-problems-ba2d86ac5837)
