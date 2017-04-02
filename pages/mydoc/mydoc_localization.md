---
title: Localization
tags:
keywords:
toc: false
summary: "TP is committed to provide a high-quality experience to international customers"
sidebar: mydoc_sidebar
permalink: mydoc_localization.html
folder: mydoc
---

## Think About Global Users

### Be Aware of the Cultural Significance of Colors
For example, the color red is associated with warning and danger in Western cultures, while it symbolizes luck and happiness in some Asian cultures, like China and Japan.

### Avoid Using Flags to Represent Languages
Language and country are different concepts. Flags are symbols that represent countries or nations while languages represent a shared method of communication between people. For example, Spanish is spoken in 29 countries and Spain is only one of them. Countries like Canada have more than 1 official language. Which language do you think the maple flag represents?

When designing a language selector, use plain text despite its lack of visual appeal. Only use flags to represent countries, not languages.

## Design for Text Expansion

When English text gets translated to another language, the translated text can be as much as three times longer. Leave blank space around condensed UI components, such as buttons and tabs.

Make UI components expandable whenever possible. Do not assign a fixed-width or height to your UI component unless you have a good reason.

For longer text, wrapping is a good solution. Be aware of the potential vertical expansion since translated text will take more lines.

Truncation with hover text can be a compromise. Be aware that this brings the risk of making the UI less effective.

## Make Your CSS Localization-Friendly

## Text Length and Size Expansion Considerations

When UI text gets translated into another language, the text length often changes. For example, English is a very compact language, leading to longer translated text in most cases.  

The general rule for text expansion is: “the shorter the English text, the longer the translated text is likely to be”. The following table shows the average text expansion rate for different English text lengths from IBM’s localization guidelines.  

In general, Asian languages are more space-friendly since they tend to be more compact than European languages. But there’s no “always”. CJK (Chinese, Japanese and Korean) languages have more complicated characters than Latin characters and their characters tend to be more square, thus taking more horizontal space. Japanese is especially problematic due to it’s use of Katakana for transliteration of foreign words. For example, “Follow” in English and Japanese both have 6 characters, but Japanese is 20% longer than English due to wider characters.
