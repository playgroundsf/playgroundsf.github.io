---
title: Data Entry
tags:
keywords:
summary: "TP users need to create, add, change, delete information frequently. We use a variety of text entry and selection options to facilitate this user interaction."
sidebar: mydoc_sidebar
permalink: mydoc_dataEntry.html
folder: mydoc
---

## 1. Basic Text Input

_This is the simplest method of freeform data entry, for single or multiple lines of text._  

To limit the amount of text, use a single­line input. To restrict the type of input, you can specify the format, such as number or email address.

Multiline text areas allow the user to enter long­form plain text. You can’t specify a format to restrict the type of content.

Label the input area above or to the left of the field. In most contexts, a stacked label (label on top) is better for readability and clarity. Use horizontal labels only if you need to save vertical real estate and have fewer than 10 fields.

To group related fields together, such as individual parts of an address, use compound inputs.

### Input Help
To assist the users, you can add help text. If the explanation is lengthy, use an “info” icon and tooltip. For brief explanations (shorter than a sentence), you can place the text underneath the field.

You can also use placeholder text to provide an example of the type of input required. For example, in a Name field, show a name in the correct format.

## 2. Complex Text input

_Complex text inputs provide users with additional assistance in specific types of data entry._  

### Date Pickers

Instead of forcing the user to manually type a date, a datepicker provides a visual way for the user to browse and select a single date or range of dates.

### Lookups

A lookup allows the user to search a database for records to fill a field. The lookup can either limit the user to a single record or allow for multiple records to populate a single field.

## 3. Selection Input

_Selection inputs allow a user to choose between a limited number of options for a given field._  

### Checkboxes
Use a single checkbox for Boolean fields in which the user can choose only between true and false or on and off.

### Radio lists
A radio list allows the user to select one option from a short list (fewer than 10 options). You must have enough space to present all options together to make comparison easy. Typically, radio lists are presented as a standalone field, such as a poll within a feed, and not used in a larger form.

### Checkbox Toggle

A toggle is similar to a checkbox in that it presents users with a binary choice for an item. However, a toggle is self-contained — think of it as a short form with only one field. When user turns a toggle on or off, the change for that item is saved immediately.  

Toggles are useful for reducing ambiguity. Since toggles save immediately, what users see on the page is always a clean state (never an unsaved/dirty state).  

Use a toggle if the field you’re building:

- Exists on a page with no other form components that can appear in unsaved states.
- Can be saved independently of other fields on the page
- Semantically fits the on/off model  

A toggle is always accompanied by two external labels:

- Field label, which describes the item that the user is modifying, e.g. Post sharing, Desktop notifications, etc.
- State label, which describes the current state of the field. This label is binary and works in conjunction with the on/off state, but it’s more contextual to the field. E.g. Disabled/Enabled, Not Allowed/Allowed, etc.

### Picklists/Dropdown Menus

Picklists, commonly known as dropdown menus, allow the user to select one option or multiple options from a list. Picklists are used instead of radio lists and checkbox lists inside of a larger form. They provide more flexibility in the number of options the user can choose from.

### Dueling Picklists

Use this control when the user needs to select more than one option and define the order of the selected items.

### Inline Edit

Inline editing allows the user to edit some part of a record without making a major switch between viewing and editing. This is a highly efficient method of updating a record. A user can make their changes without losing context and they can immediately return to what they were doing before.

A field that can be edited inline will have a pencil icon next to it. The user can either double click on the field value or click on the pencil icon to activate inline edit.
