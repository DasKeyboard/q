


<div class="endpoint-container">
GET /signals/shadows
</div>

The shadows is the list of the most recent signals for each zone.
The shadows all devices can be fetched by making a GET HTTP request.


#### Request parameters
None


##### Request

<!-- Tab panes -->
<div class="tab-content cloud-or-local-tab-content">

<!-- Nav tabs -->
<ul class="nav nav-pills mb-3 cloud-or-local-nav" id="pills-tab" role="tablist">
  <li class="nav-item">
    <a class="nav-link cloud-server active" id="get-all-shadow-signals-cloud-tab"  data-toggle="pill"  href="#get-all-shadow-signals-cloud" role="tab" aria-controls="get-all-shadow-signals-cloud" aria-selected="true">Q Cloud</a>
  </li>
  <li class="nav-item">
    <a class="nav-link localhost-server" id="get-all-shadow-signals-local-tab"  data-toggle="pill"  href="#get-all-shadow-signals-local"  role="tab" aria-controls="get-all-shadow-signals-local" aria-selected="false">Localhost</a>
  </li>
</ul>

<!-- Cloud code example -->
<div class="tab-pane active" id="get-all-shadow-signals-cloud" role="tabpanel" aria-labelledby="get-all-shadow-signals-cloud-tab" markdown="1">
{% include /script-examples/signal-resource/get-all-shadow-signals/cloud/with-api-key/index.md %}
</div>

<!-- Local example -->
<div class="tab-pane" id="get-all-shadow-signals-local" role="tabpanel" aria-labelledby="get-all-shadow-signals-local-tab" markdown="1">
{% include /script-examples/signal-resource/get-all-shadow-signals/local/index.md %}
</div>
</div>

##### Response



<div class="code-response" markdown="1">

```json
HTTP 200
[
  {
    "clientName": "ZAPIER",
    "color": "#00FF00",
    "createdAt": 1532970435297,
    "effect": "BLINK",
    "id": 1308193,
    "isArchived": false,
    "isMuted": false,
    "message": "Social media helps solve mystery of skier who disappeared in the Alps in 1954",
    "name": "NEWS",
    "pid": "DK5QPID",
    "updatedAt": 1532970435299,
    "userId": 9,
    "zoneId": "78"
  },
  {
    "clientName": "",
    "color": "#00F",
    "createdAt": 1532957910711,
    "effect": "SET_COLOR",
    "id": 1307671,
    "isArchived": false,
    "isMuted": false,
    "message": "Monday: A longer and more intense wildfire season, a divisive rent control initiative, and Berkeley on a budget.https://www.nytimes.com/2018/07/30/us/california-today-firefighters.html",
    "name": "new york times: California Today: The Increasing Strain on State Firefighters",
    "pid": "DK5QPID",
    "updatedAt": 1532957910713,
    "userId": 9,
    "zoneId": "128"
  }
]
```

</div>