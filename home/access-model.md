---
description: "Internal and external access model."
icon: user-lock
---

# Access model

{% tabs %}
{% tab title="External" %}
Partners, contractors and end users see approved overviews, setup guidance and partner-safe updates.
{% endtab %}
{% tab title="Internal" %}
SITA employees see implementation notes, LMS links, internal support routes and draft guidance.
{% endtab %}
{% tab title="Reviewer" %}
Product teams can comment, request edits and approve without becoming the page owners.
{% endtab %}
{% endtabs %}

{% if visitor.claims.unsigned.persona === "internal" %}

{% hint style="warning" %}
Internal-only example: commercial notes, roadmap context and internal SharePoint links would appear here.
{% endhint %}

{% endif %}

{% if visitor.claims.unsigned.persona === "partner" %}

{% hint style="info" %}
Partner view example: show approved deployment guidance and partner-safe support routes.
{% endhint %}

{% endif %}
