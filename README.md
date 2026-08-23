# Digital-closet-BA-case-study
### A Business Analyst Case Study

A mobile app concept that helps users digitize their wardrobe,
build outfits, and plan what to wear ahead of trips and events. This repo
documents the full Business Analyst process behind it: from problem
identification through business requirements, market positioning, process
design, and UI reference — built as a solo portfolio project.

> **Status:** Portfolio/case study project, not a shipped product. No
> development team, no funding, no real users. See [What's Not Done](#whats-not-done--next-steps)
> for open items.

---

## Table of Contents

- [The Problem](#the-problem)
- [My Role](#my-role)
- [Scope](#scope)
- [Market Context](#market-context)
- [Process Flow](#process-flow)
- [Solution Overview](#solution-overview)
- [Screens](#screens)
- [Documentation](#documentation)
- [What's Not Done / Next Steps](#whats-not-done--next-steps)

---

## The Problem

Users, mainly women, a lot of the times, can spend significant time and effort browsing their
closet and putting together outfits, especially when preparing for an
event or packing for a trip.

**Root causes:**
- The closet only exists physically, with no digital record.
- For users who own a large number of items, there's no efficient way to
  search or filter by criteria (color, type, occasion).
- There's nowhere to save past outfit combinations -> so styling
  effort mostly has to be repeated from scratch each time.

This isn't a hypothetical problem invented for the case study but
based on the project owner's own experience managing a wardrobe (has not
been validated through formal user interviews.

## My Role

Solo Business Analyst -- sole owner of this case study, from requirements
through process design and market analysis. No PM, PO, designer, or dev
team was involved; those roles are listed as *possible* stakeholders in
the BRD to reflect a realistic project structure, not because they were
staffed.

**Responsibilities:** requirements gathering, process/gap analysis, market
research, business rules definition, Epic breakdown, and coordinating the
UI reference design (built with Figma AI-assisted design tools).

## Scope

**Platform:** Mobile-only (iOS/Android).

| Priority | Features |
|---|---|
| **Must-have** | Account & login, personal profile (measurements, personal color), item add/edit/delete with photo, hashtags & notes, closet grid/list view, hashtag search |
| **Should-have** | Automatic background removal, Look (outfit canvas), Collection (grouping), Trip (day-by-day outfit planning) |
| **Could-have** | Customizable app theme |
| **Out of scope (this phase)** | Digital mannequin (virtual try-on), AI outfit suggestion |

## Market Context

Digital wardrobe apps are an established category, not an empty market --
Stylebook, Whering, Acloset, Cladwell, Smart Closet, and others already
serve this space, with Acloset alone reporting around 8 million users.

Being upfront about positioning: most of the idea's Must/Should-have scope
overlaps with what these apps already do (manual cataloging, outfit
canvas, trip/packing planning). The main point of difference is scope
discipline -- deliberately excluding AI tagging and outfit suggestion
(unlike Acloset, Cladwell, Outflik) to stay in fully manual, user-controlled
territory, while avoiding pain points reported in the closest manual-first
competitor, Stylebook (iOS-only, one-time paywall, hours-long setup).

Full competitor breakdown and gap analysis: see the [BRD],
Section 4.

## Process Flow

### As-Is: Current Manual Process
![As-Is process diagram](As-is%20process%20diagram.png)

Today, without any app, users either dig through their physical closet
item by item or follow no fixed process at all. Both paths lead to the
same two consequences: **forgetting items they own**, and **the outfit
combination never being saved anywhere** once decided.

### To-Be: Capsule Process

![To-Be process diagram](To-Be%20process%20diagram.png)

With the app, the user opens the app and either searches by hashtag or
browses the closet directly, selects items, combines them into a Look,
and saves it. From there the Look can serve a single occasion, get filed
into a Collection, or get assigned to a specific day of a Trip. Every path
converges on a saved, reusable outcome -- directly closing both gaps shown
in the As-Is diagram.

## Solution Overview

Requirements are grouped into five Epics, each tied to a business
objective:

| Epic | Business Objective |
|---|---|
| **Account & Profile** | Let users securely own and personalize their closet data |
| **Closet Management** | Let users digitize, organize, and quickly retrieve items |
| **Outfit Styling (Look)** | Let users build and save reusable outfit combinations |
| **Organization (Collection)** | Let users group items/Looks around their own categories |
| **Trip Planning** | Let users plan outfits ahead of a trip or event |

## Screens

UI reference designs, built with Figma AI-assisted design tools.

| | | |
|---|---|---|
| ![Login/Sign up](Visual%20Demo/1.login-signup.png) Login / Sign-up | ![Profile](Visual%20Demo/2.profile-personal-info.png) Profile & Personal Info | ![Wardrobe Home](Visual%20Demo/3.wardrobe-home.png) Wardrobe Home |
| ![Camera Capture](Visual%20Demo/4.camera-capture.png) Add Item (background removal) | ![Item Detail](Visual%20Demo/5.item-detail.png) Item Detail | ![Outfit Builder](Visual%20Demo/6.outfit-builder.png) Outfit Builder (Look) |
| ![Saved Outfits](Visual%20Demo/7.saved-outfits.png) Saved Outfits | ![Calendar Planner](Visual%20Demo/8.calendar-planner.png) Calendar Planner | ![Collections](Visual%20Demo/9.collections.png) Collections |
| ![Trip Planner](Visual%20Demo/10.trip-planner.png) Trip Planner | | |

## Documentation

| Artifact | Description |
|---|---|
| [Business Requirements Document](BRD%20document/BRD_Digital_Closet.docx) | Business objectives, current-state analysis, market & gap analysis, business rules, Epics, stakeholders, risks, dependencies |

## What's Not Done / Next Steps

Kept visible deliberately -- an honest map of what this case study does
and doesn't cover yet:

- **No formal user research** -- pain points are based on the project
  owner's own experience, not validated interviews.
- **No usability testing or accessibility review** conducted.
- **Platform/framework, budget, and timeline** are unresolved -- this was
  scoped as a documentation exercise, not a funded build.
- **Market differentiation is modest** -- see Market Context above; this
  is flagged as a risk in the BRD rather than glossed over.
