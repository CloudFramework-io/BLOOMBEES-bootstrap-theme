---
layout: docs
title: Tables
group: components-css
---

### Description

| Class | Description |
|-------|-------------|
| `.table` | Adds basic styling (light padding and only horizontal dividers) to any <table> |
| `.table-striped` | Adds zebra-striping to any table row within <tbody> (not available in IE8) |
| `.table-bordered` | Adds border on all sides of the table and cells |
| `.table-hover` | Enables a hover state on table rows within a <tbody> |
| `.table-condensed` | Makes table more compact by cutting cell padding in half |
{:class="table table-bordered"}

The `.table-responsive` class creates a responsive table. The table will then scroll horizontally on small devices (under 768px). When viewing on anything larger than 768px wide, there is no difference:

{% example html %}
<div class="table-responsive">
    <table class="table">
        <tr>
            <th>Title 1</th>
            <th>Title 2</th>
            <th>Title 3</th>
            <th>Title 4</th>
            <th>Title 5</th>
            <th>Title 6</th>
            <th>Title ...</th>
            <th>Title n</th>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
    </table>
</div>
{% endexample %}

---

### Examples

#### `.table-hover`

{% example html %}
    <table class="table table-hover">
        <tr>
            <th>Title 1</th>
            <th>Title 2</th>
            <th>Title ...</th>
            <th>Title n</th>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
    </table>
{% endexample %}

#### `.table-bordered`

{% example html %}
    <table class="table table-bordered">
        <tr>
            <th>Title 1</th>
            <th>Title 2</th>
            <th>Title ...</th>
            <th>Title n</th>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
    </table>
{% endexample %}

#### `.table-condenced`

{% example html %}
    <table class="table table-condenced">
        <tr>
            <th>Title 1</th>
            <th>Title 2</th>
            <th>Title ...</th>
            <th>Title n</th>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
        <tr>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
            <td>Text</td>
        </tr>
    </table>
{% endexample %}

#### `.table-striped`

{% example html %}
    <table class="table table-striped">
        <head>
            <tr>
                <th>Title 1</th>
                <th>Title 2</th>
                <th>Title ...</th>
                <th>Title n</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Text</td>
                <td>Text</td>
                <td>Text</td>
                <td>Text</td>
            </tr>
            <tr>
                <td>Text</td>
                <td>Text</td>
                <td>Text</td>
                <td>Text</td>
            </tr>
        </tbody>
    </table>
{% endexample %}
