# All Images

    {% for sample in samples %}
<a href="{{sample.url}}">
    <h2>{{sample.thumbnail}}</h2>
    <img src="../../img/thumbnails/{{ sample.name }}.png" width="302" alt="{{sample.name}}" data-fullsize="{{sample.thumbnail}}" data-orig="../../img/thumbnails/{{ sample.name }}.png"/>
</a>
<hr/>
    {% endfor %}
    </ul>

<img src="https://telemetry.sharepointpnp.com/teams-dev-samples/docs/samples/thumbs" />