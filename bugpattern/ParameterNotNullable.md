---
title: ParameterNotNullable
summary: Method parameters that aren't checked for null shouldn't be annotated @Nullable
layout: bugpattern
tags: ''
severity: SUGGESTION
providesFix: NO_FIX
---

<!--
*** AUTO-GENERATED, DO NOT MODIFY ***
To make changes, edit the @BugPattern annotation or the explanation in docs/bugpattern.
-->

## The problem


## Suppression
Suppress false positives by adding an `@SuppressWarnings("ParameterNotNullable")` annotation to the enclosing element.