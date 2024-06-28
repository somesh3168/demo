---
layout: prod
title: Belform Products
---

<style>

    .column_f {
        float: left;
        width: 33%;
        padding: 0 10px;
    }
    .row_f {margin: 0 -5px;}
    .row_f:after {
        content: "";
        display: table;
        clear: both;
    }
    @media screen and (max-width: 700px) {
        .column_f {
        width: 100%;
        display: block;
        margin-bottom: 20px;
        }
    }
    .card_f {
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
        border-radius: 5px;
        padding: 7px;
        text-align: center;
        background-color: #f1f1f1;
        margin-top: 1.5rem;
    }
    .card_f img{
        height: 100%;
        object-fit: cover;
        max-height: 100%;
        width:100%;
        height: 400px;
        border-radius: 5px;
        cursor: pointer;
    }
</style>


<h2>Products</h2>

<div class="row_f">
    {% for product in site.prods %}
    <div class="column_f">
        <div class="card_f">
        <h2><a href="{{ product.url }}">{{ product.title }}</a></h2>
            <a href="{{ product.url }}">
            <img src="{{ product.image_url }}" alt="{{ product.title_1 }}">
            <div class="caption">{{ product.title_1 }}</div>
            </a>
            <p>{{ product.content | strip_html | truncatewords:50 }}</p>
            <button onclick="location.href='{{ product.url }}'">Open</button>
        </div>
    </div>
    {% endfor %}
</div>
