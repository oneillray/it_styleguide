---
layout: page
title: Buttons
---

Buttons are used for **actions**, like in forms, while textual hyperlinks are used for **destinations**, or moving from one page to another.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Default buttons

Use the standard—yet classy—`.it-btn` for form actions and primary page actions. These are used extensively around the site.

When using a `<button>` element, **always specify a `type`**. When using a `<a>` element, **always add `role="button"` for accessibility**.

{% example html %}
<button class="it-btn it-btn--primary" type="button">Button </button>
<a class="it-btn it-btn--link" href="#" role="button">Link button</a>
{% endexample %}

You can find them in three sizes sizes: the default `.it-btn` and the smaller `.it-btn--sm` and larger `.it-btn--lg` .

{% example html %}
<button class="it-btn it-btn--primary" type="button">Button</button>
<button class="it-btn it-btn--primary it-btn--sm" type="button">Small button</button>
{% endexample %}

### Alternate base (generic) 
{% example html %}
<button class="it-btn it-btn--generic" type="button">Button</button>
<button class="it-btn it-btn--generic it-btn-sm" type="button">Small button</button>
{% endexample %}

## Outline

Outline buttons are worker buttons and are used to indicate the *utility* action on a page. When you need your buttons to stand out, use `.it-btn.it-btn--outline`. You can use it with both button sizes—just add `.it-btn--outline`.

{% example html %}
<button class="it-btn it-btn--outline" type="button">Utility </button>
<button class="it-btn it-btn--sm it-btn--outline" type="button">Small utility </button>
{% endexample %}


## Subscribe

Subscribe buttons are yellow and are used to indicate the main *cta* actions on a page to drive subscribtions. When you need your buttons to stand out, use `.it-btn.it-btn--subscribe`. You can use it with both button sizes—just add `.it-btn--subscribe`.

{% example html %}
<button class="it-btn it-btn--subscribe" type="button">Subscribe </button>
<button class="it-btn it-btn-sm it-btn--subscribe" type="button">Small primary button</button>
{% endexample %}

## Disabled state

Disable `<button>` elements with the boolean `disabled` attribute and `<a>` elements with the `.disabled` class.

{% example html %}
<button class="it-btn" type="button" disabled>Disabled button</button>
<a class="it-btn it-btn--disabled" href="#" role="button">Disabled button</a>
{% endexample %}

Similar styles are applied to primary, danger, and outline buttons:

{% example html %}
<button class="it-btn it-btn--primary" type="button" disabled>Disabled button</button>
<a class="it-btn it-btn--primary it-btn--disabled" href="#" role="button">Disabled button</a>
{% endexample %}


{% example html %}
<button class="it-btn it-btn--outline" type="button" disabled>Disabled button</button>
<a class="it-btn it-btn--outline disabled" href="#" role="button">Disabled button</a>
{% endexample %}


## With Icons

{% example html %}
<button class="it-btn it-btn--outline" type="button" disabled>Disabled button</button>
<a class="it-btn it-btn--outline disabled" href="#" role="button">Disabled button</a>
{% endexample %}


## With Sub-line

Buttons with Sub-line are common in the subscription page buttons. 

{% example html %}
<button class="it-btn it-btn--subscribe it-btn--double-line" type="button">Subscribe </button>
<button class="it-btn it-btn-sm it-btn--subscribe it-btn--double-line" type="button">Small primary button</button>
{% endexample %}

## With Icon

{% example html %}
<button class="it-btn it-btn--primary it-btn--icon">
<i class="fa fa-eye"></i> Read More</button>
{% endexample %}


## Link button

{% example html %}
<a href="" class="it-btn it-btn--link">Click here</a>
{% endexample %}
