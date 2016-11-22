---
layout : default
---

<div class="row">
    {% for post in site.posts %}
    <div class="col-sm-4">
        <div class="panel panel-success">
            <div class="panel-heading">
                <h3 class="panel-title">{{post.title}}</h3>
            </div>
            <div class="panel-body">{{post.content}}</div>
        </div>
    </div>
    {% endfor %}
</div>