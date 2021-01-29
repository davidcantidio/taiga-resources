---
title: "Customisation"
date: 2020-10-05T11:27:41+02:00
draft: false
image: "images/customization.png"
type: "feature"
main: true
order: 4

# taxonomies
categories:
  - "customisation"
---

No two teams, projects or organisations are alike. Learn how we elegantly crushed the one-size-fits-all curse. Both lack of flexibility and extreme configurability plague the project management arena. Taiga's approach is simple: keep consistency throughout projects, regardless of their simple or advanced status, and outsource some ad-hoc decision to the team's real-world interactions.

This content is specially useful for any Taiga user that has at least admin rights on any project, since most of what we will cover do require ADMIN status. You can give ADMIN status to anyone in your project under PROJECT > MEMBERS regardless of their project role. 

### Tier 1: Modules selection and Default values

This might seem obvious but it's worth mentioning. One of the most profound ways to customise a project is to select which modules are available. Depending on this, a team might lean towards one way or another regarding project management. 

The Modules that are available are Epics, Scrum, KANBAN, Issues, Wiki and Meetup. Scrum and Meetup require some minimum configuration but the rest are fine just being activated.

{{< figure src="/images/modulesactivation.png" caption="Module activation panel under PROJECT > SETTINGS > MODULES" alt="Module activation panel under PROJECT > SETTINGS > MODULES" width="100%" class="articlefigure" >}}


{{< figure src="/images/defaultvalues.jpg" caption="A sample WIKI page by a The Princess Bride fan. Images, text, tables, code, attachments and a bit of activity" alt="A sample WIKI page by a The Princess Bride fan. Images, text, tables, code, attachments and a bit of activity" width="100%" class="articlefigure" >}}


At first glance, **Issues is just a long list of stuff where pagination reigns**. It's when you start using it that you find all the hidden gems. You can activate Issues going to SETTINGS > PROJECT > MODULES and clicking on the Issues toggle. You will immediately see the Issues icon pop up at the upper section of the side navigation bar. 

First of all, Issues can **contain any type of work item**. Don't be limited to "bugs", that's not how we see things here at Taiga. You get a default setup for three Issue types **you can always change** under SETTINGS > ATTRIBUTES > TYPES. An Issue Type could be a "Threat", "Purchase order" or "Sales call", it could be anything as long as it feels like a **big enough category** for the team. For the rest of this article let's assume you are happy with Bugs, Questions and Enhancements, which is quite common in Engineering Projects.

Issues is not afraid of super long lists, **it's meant to cope with that thanks to its 30 items per page**. So be free to bulk-add issues if they fit into the default Issue TYPE category. What Issues requires to be useful for teams is to have some attribute setting per issue. **Type** is mandatory but so it's **Severity** and **Priority**, so wisely choose default values for them under SETTINGS > ATTRIBUTES > [SEVERITIES or PRIORITIES].

The default ordering mechanism for Issues unless you click on the other columns is "Modified". **Any time you create or change an issue, it will bubble up through the list**. This means that more active or newer issues appear at the top while long forgotten or closed issues naturally sink in the pagination layout. However, you're one click away to order your zillion issues by Severity or Assigned team member, for example.

### Tier 2: Workflows editing
Type, Severity and Priority

Page for Customisation


### Tier 3: Permission & Roles configuration 
Type, Severity and Priority

Page for Customisation


### Tier 4: 3rd party integrations 
Type, Severity and Priority

Page for Customisation


### Tier 5: Custom fields and Due Dates 
Type, Severity and Priority

Page for Customisation
