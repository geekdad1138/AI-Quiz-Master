# Quiz Schema Documentation

This document defines the standardized markdown format for all quizzes in the AI Quiz Master project.

## Overview

All quizzes are written in markdown to ensure flexibility in conversion to PDF, web, CLI, or other formats.

## Quiz File Structure

```markdown
# Quiz Title

**Category**: [school|professional|master-class]
**Level**: [introductory|beginner|intermediate|advanced]
**Topics**: [comma-separated topic tags]
**Questions**: [number of questions]

---

## About This Quiz

Brief description of what this quiz covers, learning outcomes, and target audience.

---

## Questions

### Question 1
**Type**: [multiple-choice|true-false|matching|short-answer]
**Difficulty**: [easy|medium|hard]

**Question Text**

What is the primary purpose of [concept]?

**Options**
- A) Option 1
- B) Option 2
- C) Option 3
- D) Option 4

**Correct Answer**: B

**Explanation**

Detailed explanation of why B is correct and why the other options are incorrect. Include relevant context or additional learning information.

---

### Question 2
[Follow the same format above]

---

## Answer Key

| Question | Answer | Difficulty |
|----------|--------|------------|
| 1        | B      | medium     |
| 2        | [ans]  | [level]    |

---

## Scoring Guide

- **90-100%**: [Mastery description]
- **80-89%**: [Proficiency description]
- **70-79%**: [Developing description]
- **Below 70%**: [Needs improvement description]

---

## Resources

- [Link to relevant resource]
- [Link to reference material]
```

## Field Definitions

### Metadata
- **Category**: One of: `school`, `professional`, `master-class`
- **Level**: 
  - School: `introductory` (K-5), `beginner` (6-8), `intermediate` (9-12)
  - Professional: `beginner`, `intermediate`, `advanced`
  - Master-class: `comprehensive`
- **Topics**: Comma-separated tags for categorization
- **Questions**: Total number of questions in quiz

### Question Fields
- **Type**: 
  - `multiple-choice` (4 options)
  - `true-false`
  - `matching` (list items to match)
  - `short-answer` (open-ended, graded subjectively)
- **Difficulty**: `easy`, `medium`, `hard`
- **Correct Answer**: Letter (A-D), true/false, or text
- **Explanation**: Detailed reasoning and context

## Example Quiz

```markdown
# Introduction to Machine Learning Concepts

**Category**: professional
**Level**: beginner
**Topics**: machine-learning, fundamentals
**Questions**: 5

---

## About This Quiz

This quiz assesses foundational knowledge of machine learning concepts. It covers the definition of machine learning, types of learning, and basic terminology. Suitable for anyone beginning to learn about AI and ML.

---

## Questions

### Question 1
**Type**: multiple-choice
**Difficulty**: easy

**Which of the following best defines Machine Learning?**

- A) A computer program that can play games
- B) A subset of artificial intelligence where systems learn patterns from data
- C) A type of software that manages databases
- D) An algorithm that sorts information

**Correct Answer**: B

**Explanation**

Machine Learning is a subset of artificial intelligence that focuses on systems learning from data without being explicitly programmed. Option A describes gaming AI specifically. Option C describes database management. Option D describes a specific algorithmic task, not ML as a whole.

---

### Question 2
**Type**: true-false
**Difficulty**: easy

**True or False: Supervised learning requires labeled training data.**

**Correct Answer**: True

**Explanation**

Supervised learning uses labeled training data where each example has both input and expected output. The "labels" guide the learning process. Unsupervised learning, by contrast, works with unlabeled data.

---

## Answer Key

| Question | Answer | Difficulty |
|----------|--------|------------|
| 1        | B      | easy       |
| 2        | True   | easy       |
| 3        | A      | easy       |
| 4        | C      | medium     |
| 5        | B      | medium     |

---

## Scoring Guide

- **100%**: Complete mastery of ML fundamentals
- **80-99%**: Strong understanding, ready for intermediate content
- **60-79%**: Foundational knowledge present, recommend review
- **Below 60%**: Recommend foundational resources and retry

---

## Resources

- [Machine Learning Basics](https://example.com)
- [Supervised vs Unsupervised Learning](https://example.com)
```

## Best Practices

1. **Clarity**: Questions should be unambiguous and clearly worded
2. **Accuracy**: Ensure all content is factually correct and current
3. **Pedagogy**: Explanations should teach, not just confirm answers
4. **Consistency**: Follow the schema exactly for conversion automation
5. **Accessibility**: Use clear language appropriate for the target level
6. **Balance**: Mix difficulty levels to create engaging assessments

## Future Enhancements

As we develop conversion tools, this schema may be extended to support:
- Question images/diagrams
- Code snippets in questions
- Interactive elements
- Scoring algorithms
- Prerequisite tracking
