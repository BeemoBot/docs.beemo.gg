---
layout: default
title: Preset Reasons
parent: Moderation
nav_order: 3
---

# Preset Reasons

Save your moderators' time by storing preset reasons to use when making redundant moderation actions. 
{: .fs-6 .fw-300 }

---

## About
Preset reasons allow moderators to save time when issuing punishments by using preset flags for reasons that are repeatedly used (like canned responses for moderators!)

## Configuration
Configuring preset reasons for your server is simple. However, please keep in mind that you must have the `Administrator` permission or be a Moderation Manager to configure preset reasons. 

### Managing Presets

To set a new preset reason, do `/mod presetreason [preset name] (reason)`, to remove a preset reason, do `/mod presetreason [preset name]` without a reason.

Once added, all moderators in your server will now be able to use the preset reason you have configured by simply typing `-reasonhere` as their reason.

### Viewing/Listing Presets
To list all of the available preset reasons, use the `/presetreasons` command, to see a specific reason, do `/presetreasons -reasonhere`.

### Using Presets

To use a preset reason in a moderation command, simply put `-reasonhere` as your reason at the end of the moderation command, and Beemo will automatically action the user with that reason. You can also use the `/edit (case id) -presetreasonhere` to apply a preset reason to an existing case.

