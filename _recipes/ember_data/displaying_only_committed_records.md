---
title: Displaying only committed records
section: Ember Data
layout: default
---
## Problem

You want to display only the committed `DS.Model` records from the ArrayController `content` array.

## Solution

In order to not show the uncommitted records of your array, you should filter them on `isNew` property.

## Discussion
