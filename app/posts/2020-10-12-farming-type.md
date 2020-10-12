---
title: Farming business type
description: Asking the type of farming business
date: 2020-10-04
---

## Overview

### Hypothesis

Only specific farming businesses can apply. We need to know if the business meets this requirement.

### User needs

As an applicant for a large grant, I need:

* to know if their farm business is eligible to apply for the grant

As a government agency offering a large grant, I need:

* to check that a farm business eligible for the scheme is applying

***

## Version 1

### Design

#### Question page

Question and option buttons.

Options available are only those types of farming eligible for water resource management grants.

Select 'other' and get a fail page.

#### Fail page
First iteration included “large countryside productivity grant”. Wording makes it clear which grant it is.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [
    {
      text: "V1 farming type"
    },
    {
      text: "V1 farming type fail"
    }
  ]
}) }}

### User research

#### Key points

* Users can be both arable and horticulture
* Distinction between arable and horticulture is a grey area

#### Suggestions

Make it clear this question is about grant related activity.

Provide guidance about how Defra distinguishes between arable and horticulture - changing to a yes/no question meant this was not needed.

Checked with policy and didn’t need to know exactly what they did, just that they did one of the activities that can qualify for this water grant.

#### Participant comments

* P30 - grows potatoes, but doesn’t consider this a horticultural business
* P30 - I want to click on 2 things
* P30 - what type of farming do you do? Not what type of farming will you use your water grant for?

***

## Version 2

### Design

Content project specific not business.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [
    {
      text: "V2 farming type water"
    },
    {
      text: "V2 farming type water fail"
    },
    {
      text: "v2 farming type slurry"
    },
    {
      text: "v2 farming type slurry fail"
    }
  ]
}) }}
