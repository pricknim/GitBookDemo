---
description: Some of the advanced blocks
cover: https://istccorp.com/wp-content/uploads/2021/04/bosch-header.jpg
coverY: 260
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Advanced blocks

{% file src="../../.gitbook/assets/example.txt" %}
This in an example txt file
{% endfile %}

<figure><img src="https://i.insider.com/5980b7ca87543302234a1a57?width=800&#x26;format=jpeg&#x26;auto=webp" alt="" width="375"><figcaption><p>This is an example image block using an url</p></figcaption></figure>

{% embed url="https://www.google.com/" %}
This is an example embeded URL
{% endembed %}

<table><thead><tr><th valign="top">Example</th><th data-type="checkbox"></th><th data-type="rating" data-max="5"></th><th data-type="users" data-multiple></th></tr></thead><tbody><tr><td valign="top"><a data-footnote-ref href="#user-content-fn-1">With</a></td><td>true</td><td>null</td><td><a href="https://app.gitbook.com/u/TUs2qzHmbYdBoBEnU5eo7IeRA8x1">niko.domokos</a></td></tr><tr><td valign="top">Interesting</td><td>true</td><td>4</td><td></td></tr><tr><td valign="top">Columns</td><td>false</td><td>2</td><td></td></tr></tbody></table>



<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-type="rating" data-max="5"></th><th data-type="number"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td>This a card example</td><td></td><td></td><td>4</td><td>null</td><td><a href="../../.gitbook/assets/asd.png">asd.png</a></td></tr><tr><td></td><td></td><td></td><td>null</td><td>null</td><td></td></tr></tbody></table>

{% tabs %}
{% tab title="First Tab" %}
This is the first tab

Just about anything can be placed inside a tab.
{% endtab %}

{% tab title="Second Tab" %}
This is the second tab
{% endtab %}
{% endtabs %}

<details>

<summary>Expandable</summary>

Expandable content

These are the only insertable options here

![](../../.gitbook/assets/image.png)

</details>

{% stepper %}
{% step %}
### Name of Step 1

Create a stepper
{% endstep %}

{% step %}
### Name of Step 2

Add example description to stepper
{% endstep %}
{% endstepper %}

<img src="../../.gitbook/assets/file.excalidraw.svg" alt="This is a drawing made in the gitbook ui" class="gitbook-drawing">







[^1]: Annotation example
