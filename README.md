# SiteCrafting jQuery Accordion Plugin

A simple jQuery plugin for displaying accordions. Requires jQuery to be installed and included on the page prior to being called.

## Installation

`yarn add sitecrafting-jquery-accordion`

## Usage

### JS
```
import accordion from 'sitecrafting-jquery-accordion';

$.fn.accordion = accordion;
$('dl.accordion').accordion();
```

### HTML

```
<dl class="accordion">
    <dt data-id="tab1"><h3><a href="#tab1">Tab Title</a></h3></dt>
    <dd>Panel Content</dd>
    <dt data-id="tab1"><h3><a href="#tab2">Tab Title</a></h3></dt>
    <dd>Panel Content</dd>
</dl>
```