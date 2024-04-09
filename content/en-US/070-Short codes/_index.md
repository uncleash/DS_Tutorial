---
title: "Short codes and placeholders"
chapter: true
weight: 80
---

### Short codes and placeholders allow you to add some dynamic content and insert special media and pre-formatted text to your demo script  


* Youtube frame (use youtube video id):
```
{{< youtube neeXDdT6m1U >}}
```

* Vimeo frame (use video id):
```
{{< vimeo 771585197 >}}
```

* Mp4 video frame:
```
{{< video https://some-host.com/file.mp4 >}}
```

* Phone numbers - a dynamic list of demo phone numbers specific to the demo user region:

```
{{% phone numbers %}}
```

* Warning notice:
```
{{% notice warning %}}
Some important warning text is here....
{{% /notice %}}
```

* Info notice:

```
{{% notice info %}}
Some information is here....
{{% /notice %}}
```

* Note notice:

```
{{% notice info %}}
Some notes are here....
{{% /notice %}}
```

* Tip notice:

```
{{% notice tip %}}
Some interesting tip is here....
{{% /notice %}}
```

* Collapsible info block:

```
{{% collapse info title="...." }}%
Some interesting tip is here....
{{% /collapse %}}
```

* Collapsible warning block:

```
{{% collapse warning title="...." }}%
Some warning is here.... 
{{% /collapse %}}
```

### Placeholders

Placeholder help you with adding of some dynamic information to your demo script. Like first or last name of the GDemo user, his email address, etc:

| Placeholder | Replacement |
|--- | --- |
| #gsys_username | GDemo username |
| #gsys_firstname | First name |
| #gsys_lastname | Last name |
| #gsys_gdemo_id | GDemo ID |
| #gsys_email | Email address |
| #gsys_phone | Phone number |
| #gsys_address | Address |
| #gsys_city | City |
| #gsys_country | Country |
| #gsys_pc_region | GC Region |
| #gsys_pc_skill1 | GC Skill 1 |
| #gsys_pc_skill2 | GC Skill 2 |
| #gsys_ext_contact | GC External contact ID |

***Example:***

```
Please make a call from #gsys_phone phone number.
```

