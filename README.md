# en-650-663-01-lab-1-write-an-appengine-standard-app-solved
**TO GET THIS SOLUTION VISIT:** [EN.650.663-01 Lab 1-Write an “AppEngine Standard” App Solved](https://www.ankitcodinghub.com/product/en-650-663-01-lab-1-write-an-appengine-standard-app-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94931&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EN.650.663-01 Lab 1-Write an “AppEngine Standard” App Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
&nbsp;

<h1>Description</h1>
For this project you are going to implement and deploy a basic AppEngine (Standard, not Flex) application that keeps track of (and counts down to) upcoming events. It will have the following characteristics (note that if you are adventurous, you can use whatever language or serverless provider you like, but you might have less help):

&nbsp;

<ul>
<li>Events are displayed in “soonest first” order, ignoring non-repeating events in the past.</li>
<li>Events are stored in Cloud Datastore
<ul>
<li>name</li>
<li>date (bonus: missing year means “repeats yearly”)</li>
</ul>
</li>
<li>The main page is all static, with JavaScript<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> doing dynamic requests.<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a></li>
<li>Users can add new events from the web page (and optionally delete them).<a href="#_ftn3" name="_ftnref3"><sup>[3]</sup></a></li>
</ul>
&nbsp;

<table width="624">
<tbody>
<tr>
<td width="624">You may use any language you like. Python 3 is a solid and popular choice, but language will not be dictated in this course. Pick what you are comfortable working with, change later if you don’t like it.</td>
</tr>
</tbody>
</table>
<h1>Grading Rubric</h1>
Grading labs is always tricky business. Every lab has a minimum standard that, if you meet it, will guarantee at least a B- on that lab. Other points fit on top of that standard. If the minimum standard is not met, the grade assigned is discretionary based on how much was completed.

<h2>Minimum Requirements</h2>
<ul>
<li>All HTML and JavaScript is served statically (not generated dynamically on the server).</li>
<li>A user can
<ul>
<li>Access the web page and immediately see stored events with ETAs</li>
<li>Add a new event from that page and see it appear in the events list</li>
</ul>
</li>
<li>GET /events returns JSON containing event information</li>
<li>POST /event accepts JSON for an event, pushes it into the database, and returns a response indicating success or error, with the new event’s ID.</li>
<li>Code: all code is original work and free of debug logic.</li>
</ul>
&nbsp;

It is possible to implement these in slightly different ways. Especially in this lab, there will be some flexibility allowed in the implementation (e.g., how errors are returned, and what additional data comes in the response for a POST or DELETE request).

&nbsp;

Meeting these minimum requirements guarantees a score of 80 points on the lab.

<h2>Additional Points</h2>
Additional points can be earned, up to a maximum of 100:

<ul>
<li>5 pts: Code is well-documented and clean (e.g., if using Python you use docstrings to specify parameters and return values)</li>
<li>5 pts: DELETE /event/&lt;event_id&gt; deletes an event from the database or returns an error (including the interface to trigger it)</li>
<li>5 pts: Yearless dates work, showing time to next occurrence of a matching date (e.g., 03-01 means “every March 1st”)</li>
<li>5 pts: ETA values change every second so they’re counting down constantly.</li>
<li>5 pts: Automatic DELETE trigger for dates in the past (like a cron job that checks for old dates and deletes them)</li>
</ul>
&nbsp;

In other words, you don’t have to do all of these things to get full credit, and if you decide to do them all, it reduces the risk of partial credit keeping you from a score of 100.

<h1>The Siren’s Serverless Call</h1>
Why AppEngine, and not something like AWS Lambda or Google Cloud Functions, or something else entirely? Because

<ul>
<li>Google AppEngine Standard includes storage.</li>
<li>The free tier stays free longer and with heavier use.</li>
<li>Auth is included (for later labs) with minimal fuss.</li>
<li>It’s a good thing to know how to use, in general.</li>
</ul>
&nbsp;

Lambda-style serverless<a href="#_ftn4" name="_ftnref4"><sup>[4]</sup></a> approaches are still more cumbersome to set up than I would like, and are somewhat overhyped – there is a cost to austerity, and it often shows up in the form of increased developer complexity, particularly at first while you figure out how things fit together (for example, you need to separately provision storage/pub-sub/etc., and that is a research project all its own—that is the sole reason I don’t push AWS Lambda instead of AppEngine: setting things up is more manual there). Setting these things up also requires a solid mental model of how web technologies fit together in a real system, but that’s <em>exactly what we’re trying to learn right now</em>, so we want to not get ahead of ourselves.

&nbsp;

<table width="624">
<tbody>
<tr>
<td width="624">If you are motivated and capable, I won’t stop you from using another technology. Just be prepared to do a little extra work with a little less help if you do. I will accept a project developed on any underlying FaaS, PaaS, or even IaaS<a href="#_ftn5" name="_ftnref5"><sup>[5]</sup></a> so long as your code implements the required characteristics. If you do decide to go your own way and find it to be better in any way, please share what you did: future classes may benefit.</td>
</tr>
</tbody>
</table>
&nbsp;

There are several moving parts in this lab, so it’s going to be important to start early. The basic steps you’ll need to take are

<ol>
<li>Install the AppEngine SDK.</li>
<li>Start a new project (with an app.yaml file) the exports necessary static resources (index.html is one such static resource, scripts, images, style sheets, etc. are, too).</li>
<li>Write a simple “Hello World” application and run it locally.
<ol>
<li>This will involve authenticating using the “gcloud” command line and doing some configuration there. Find a tutorial online that can help with this.</li>
</ol>
</li>
<li>Deploy it and make sure you can access it on the web.
<ol>
<li>This will also involve using the “gcloud” command.</li>
</ol>
</li>
<li>Write an index.html that gets JSON events, displayed with computed countdowns.</li>
<li>Add a submission form for new events to the index.html file.</li>
<li>Create a GET routine to return event JSON when asked.</li>
<li>Create a POST routine to create new events when asked.</li>
<li>Optional: create a way to delete events in a DELETE routine.</li>
<li>Deploy your app and test it out (actually, do this every time you want to test something).</li>
</ol>
&nbsp;

Fortunately, none of these steps is difficult on its own, but they do have to be done mostly in order, so it’s best to get as many early steps out of the way as possible, as soon as you can, so that you can focus on getting the communication working between the browser and the server. That’s where the interesting work is, particularly if this is at all new to you.

&nbsp;

To help with those new to all of this, a few of these tasks are broken out below. This will be familiar if you have done the previous lab.

&nbsp;

If you have done something like this before, already know enough HTML and JavaScript to be dangerous, and don’t mind digging into online tutorials, you can ignore the rest of the content here.

<h1>Setting Up</h1>
This section assumes you are using AppEngine Standard<a href="#_ftn6" name="_ftnref6"><sup>[6]</sup></a> with the default settings (Cloud Datastore, Python 3, Flask).

&nbsp;

The steps you will complete for <em>project</em> setup are basically these:

<ul>
<li>Go to <a href="https://console.cloud.google.com">https://console.cloud.google.com</a> and create a new Project.</li>
<li>Use the upper-left menu to get to the <a href="https://console.cloud.google.com/appengine">AppEngine</a></li>
<li>If you’re in your new project, it will show you a “Create Application” button. Click that.</li>
<li>Choose a region. We’re in the us-east-1 region, so that will give the best latency from JHU.</li>
<li>I choose “Python”, “Standard” on the next page, but you can pick another language if you like. I would <strong>not</strong> choose “Flexible” unless you really know what you are doing.</li>
<li>Note that by default the documentation it leads you to is for Python 2. The Python 3 documentation can be found here: <a href="https://cloud.google.com/appengine/docs/standard/python3/">https://cloud.google.com/appengine/docs/standard/python3/</a></li>
<li>Follow instructions to download the cloud SDK and get it set up.</li>
<li>Do a “gcloud auth login” so that deployment can work, and your dev server can hit the database (the local development datastore is apparently deprecated).</li>
</ul>
&nbsp;

Eventually (maybe now!) you will want to go to your project’s “service accounts” and generate a JSON key file for the default appengine service account. You can then point to that file in the <a href="https://cloud.google.com/docs/authentication/production">GOOGLE_APPLICATION_CREDENTIALS</a> environment variable to make things work from your local system. I use a small bash script to point to that when running my local Flask app so that it doesn’t pollute my system with random junk. For example:

&nbsp;

<table>
<tbody>
<tr>
<td width="624">#!/bin/bash

&nbsp;

export GOOGLE_APPLICATION_CREDENTIALS=”$HOME/.config/gcloud/appengine-token.json”

export GAE_ENV=”localdev”

python main.py
</td>
</tr>
</tbody>
</table>
&nbsp;

Once you are up and running, you will need to create your HTML file that you want served. You can do this in a couple of ways:

&nbsp;

<ol>
<li>Static: you can set up your app.yaml handler for “/” to be a static directory, and place an “index.html” file in the directory you specify, or</li>
<li>Dynamic: you can write a little Python/Flask application that serves up the index.html file and specify that as the script.</li>
</ol>
&nbsp;

There are numerous “Hello, World!” AppEngine tutorials online. I would encourage you to look at these to get started.

<h1>Getting Structured Data Into a Static Page</h1>
What we’re building is known in industry as a “one-page app”. It’s a very simple one, but it has all of the right characteristics: it’s a single static page (with its JavaScript dependencies), and it updates by making background requests and rewriting itself as needed.

&nbsp;

That’s how this assignment will work. You’ll create an <em>index.html</em> file (and potentially some .js files, if you want to split those out) that never changes and is downloaded all at once when a user comes to your site. After that, DOM events will trigger your embedded JavaScript code and get data in the background, using it to change how your page looks.

&nbsp;

A useful technique for getting started when there’s a lot to do is to assume that some of the work is already done. Let’s do that. Let’s assume that the server is already built, and all we’re doing is building the web site.

&nbsp;

Specifically, let’s assume for just a moment that we <strong>already have</strong> a service that has an endpoint <strong><em>/events</em></strong>. We can issue an HTTP GET request to it using code like this<a href="#_ftn7" name="_ftnref7"><sup>[7]</sup></a>:

&nbsp;

<table>
<tbody>
<tr>
<td width="624">&lt;html&gt;

&lt;head&gt;

&lt;title&gt;My Lovely One-Page App&lt;/title&gt;

&lt;script&gt;

function reqJSON(method, url, data) {

return new Promise((resolve, reject) =&gt; {

let xhr = new XMLHttpRequest();

xhr.open(method, url);

xhr.responseType = ‘json’;

xhr.onload = () =&gt; {

if (xhr.status &gt;= 200 &amp;&amp; xhr.status &lt; 300) {

resolve({status: xhr.status, data: xhr.response});

} else {

reject({status: xhr.status, data: xhr.response});

}

};

xhr.onerror = () =&gt; {

reject({status: xhr.status, data: xhr.response});

};

xhr.send(data);

});

}

document.addEventListener(‘DOMContentLoaded’, () =&gt; {

reqJSON(‘GET’, ‘/events’)

.then(({status, data}) =&gt; {

<em>// Use the *data* argument to change what we see on the page.</em>

<em>// It will look something like this:</em>

<em>// {</em>

<em>//&nbsp;&nbsp; “events”: [</em>

<em>//&nbsp;&nbsp;&nbsp;&nbsp; {“name”: “Grandma’s Birthday”, “date”: “08-05”},</em>

<em>//&nbsp;&nbsp;&nbsp;&nbsp; {“name”: “Independence Day”, “date”: “07-04”}</em>

<em>//&nbsp;&nbsp; ]</em>

<em>// }</em>

<em>// There are better ways, but this is illustrative of the concept:</em>

let html = ”;

for (let event of data.events) {

html += `${event.name}: ${event.date}&lt;br&gt;`;

}

document.getElementById(‘events’).innerHTML = html;

})

.catch(({status, data}) =&gt; {

<em>// Display an error.</em>

document.getElementById(‘events’).innerHTML = ‘ERROR: ‘ +

JSON.stringify(data);

});

});

&lt;/script&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id=”events”&gt;&lt;/div&gt;

&lt;/body&gt;

&lt;/html&gt;
</td>
</tr>
</tbody>
</table>
&nbsp;

When <em>reqJSON</em> is called, it returns a promise that either resolves to a status and returned data (in the <strong><em>.then</em></strong> handler) or is rejected with a status and data (in the <strong><em>.catch</em></strong> handler). If you aren’t familiar with how promises work, the main thing to know is that you pass a function into .then and .catch that gets called if things are successful or fail, respectively.

&nbsp;

In the example above, we “unpack” the object passed into the “then” handler, getting its “status” and “data” values into two variables. We could also have done something like this:

&nbsp;

<table>
<tbody>
<tr>
<td width="624">reqJSON(‘GET’, ‘/events’).then(obj =&gt; {

// do stuff with obj.status and obj.data

})<em>;</em></td>
</tr>
</tbody>
</table>
&nbsp;

You can see in the long listing above how the status and data are unpacked in both <em>then</em> and <em>catch</em>, and how they are displayed in the browser window. The way these are displayed and handled

<ul>
<li>Is not terribly efficient,</li>
<li>Doesn’t allow for customization,</li>
<li>Isn’t templatized, and therefore isn’t common (nor a best practice), and</li>
<li>Doesn’t compute the time until the event, but</li>
<li>Is straightforward to understand and illustrates the important stuff.</li>
</ul>
&nbsp;

In other words, no, you probably wouldn’t set <em>innerHTML</em> in your own code, and yes, you will need to do some computations on the date, but this is good enough as an example of the fetch-and-display concept in a static web app. Note that nowhere is the server sending down HTML that <em>changes based on the request</em>. Instead it always sends down the <em>same</em> HTML and JavaScript, and then those go ask for more things that dynamically alter the page contents. That’s what we’re after; that’s essentially how a one-page app works.

&nbsp;

Note that once the <em>reqJSON</em> function is written, it can just be reused wherever you need it, including to issue POST and DELETE requests. You may need to tweak it a bit, or copy it for mutating actions, but that big chunk of space it takes up won’t be repeated for every little thing you do.

<h3>Serving Static Content and Dynamic Data Structures</h3>
Your server will need to be implemented using AppEngine, as mentioned earlier. You can choose any language you like for this. My favorite is Go, for multiple reasons, but it’s more common to start with Python.

&nbsp;

Whatever language you use, you need to minimally implement the following endpoints. For purely static files, you can set up <em>app.yaml</em> to serve them for you and skip the code part.

&nbsp;

<table width="624">
<tbody>
<tr>
<td width="72">GET</td>
<td width="96">/</td>
<td width="456">produce index.html contents</td>
</tr>
<tr>
<td width="72">GET</td>
<td width="96">/events</td>
<td width="456">produce event JSON</td>
</tr>
<tr>
<td width="72">POST</td>
<td width="96">/event</td>
<td width="456">add a new event specified in JSON</td>
</tr>
<tr>
<td width="72">POST</td>
<td width="96">/delete</td>
<td width="456">(optional) delete an existing event (figure out how to identify it!)</td>
</tr>
</tbody>
</table>
&nbsp;

If we leave out the optional deletion endpoint, that leaves a minimum of two functions you need to write in the server: one for getting a list of events, and one for adding an event. The server also needs to return the contents of <em>index.html</em> when asked for the root “/” or “/index.html” endpoint.

&nbsp;

Find a suitable tutorial for AppEngine that is in your language, and it will be sure to cover at least those things.

<h1>Cloud Datastore</h1>
You will want to store your events in a database of sorts so that you can recall them between stateless HTTP requests. Why a database? Because with platforms as a service (and functions as a service), <em>you don’t know how many copies of your code are running, and where</em>. That means you can’t rely on your server code being able to access files: you might hit a server on machine 1 with one request, then on machine 2 with a second request. If you just assume you can mutate files as your storage mechanism, you’ll be pretty severely disappointed. Thus, we use a centralized database.

&nbsp;

For our <em>static</em> files, we can think of them as <em>part of the server</em>, so they’re okay. If you have static templates that you fill out and return, those are part of your deployment, so those end up on <em>all</em> of the machines where your service is running. It’s data that you <em>mutate</em> that you have to keep centralized in a database.

&nbsp;

In the free-tier AppEngine environment, that means using Cloud Data Store. If you are using Python 3<a href="#_ftn8" name="_ftnref8"><sup>[8]</sup></a>, you will access your data via the <a href="https://cloud.google.com/appengine/docs/standard/python3/using-cloud-datastore">Cloud Datastore client library</a>. If you are using other languages, there are similar libraries available that you will need to learn.

&nbsp;

Note that there is not, for Python 3, any “local” development data store. If you use Python 2, you can use ndb to access the datastore, and that <strong>does</strong> have a local development environment, but it’s an older runtime. It’s up to you what you use; we’ll focus on Python 3.

&nbsp;

Structure your database however you want. This is a small project, so do it however you like, but think about what would happen if you suddenly had to store thousands of events. Would you do it the same way, or would you change it? If you would change it, it might be a good idea to decide either on the limits you would impose on the app’s functionality, or on how you would migrate from a less scalable approach to a more scalable approach.

&nbsp;

When you add an event, store it in the data store. The order doesn’t really matter, since part of the assignment is to sort by event “closeness” to today, anyway.

<h1>Hopefully Helpful Tidbits</h1>
Here are a few bits of important advice for the lab. They’re a bit sparse because a big part of the point of this class is to exercise our “look things up and figure things out” muscles, so it’s expected that you will use the resources available to you, including each other. Just don’t plagiarize: write your own code!

<h2>Cloud Datastore from Python</h2>
First, make sure every entity you store has a parent key. That makes it much more likely that, if you push a new value, it comes back when you immediately query it again. Without a parent key, the entity might take some time getting there, which makes weird things happen when you submit events and then expect them to come right back. The following sets up a datastore client and a parent “root” key that can be used as the parent of all entities:

&nbsp;

<table>
<tbody>
<tr>
<td width="624">from google.cloud import datastore

app = Flask(__name__)

DS = datastore.Client()

EVENT = ‘Event’ <em># Name of the event table, can be anything you like.</em>

ROOT = DS.key(‘Entities’, ‘root’) <em># Name of root key, can be anything.</em>

def put_event(name, date_str):

entity = datastore.Entity(key=DS.key(EVENT, parent=ROOT))

entity.update({‘name’: name, ‘date’: date_str})

DS.put(entity)
</td>
</tr>
</tbody>
</table>
&nbsp;

If you want to <em>query (read)</em> things, you will set the “ancestor” to be the root key (instead of “parent”) in the query or fetch statement.

<table>
<tbody>
<tr>
<td width="624">for val in DS.query(kind=EVENT, ancestor=ROOT).fetch():

# do stuff with each value in the events table.</td>
</tr>
</tbody>
</table>
&nbsp;

Note that all of this will will access <em>the production database online</em>. One way to avoid data clashes between production and development is to choose the parent key based on the “GAE_ENV” environment variable so that you can store test data separately from “running on AppEngine” data. This is up to you and 100% optional, but you should at least be aware of its existence. Here’s an example of the code.

&nbsp;

<table>
<tbody>
<tr>
<td width="624">if os.getenv(‘GAE_ENV’, ”).startswith(‘standard’):

ROOT = DS.Key(‘Entities’, ‘root’)

else:

ROOT = DS.Key(‘Entities’, ‘dev’)</td>
</tr>
</tbody>
</table>
&nbsp;

<h2>Flask and JSON</h2>
When using Flask, you’ll be providing endpoints that handle and produce JSON. Flask provides the <em>jsonify</em> library that is really useful. You can also pull JSON from <em>request.json</em> when needed. Look at the Flask documentation, run through a tutorial or two, and it should be relatively straightforward.

&nbsp;

Note again that one of the points of this course is to exercise your “look things up and figure things out” muscles, so the snippets here are purposefully a little sparse on information. Use whatever information sources you can, including each other, just write your own code!

<h2>Date Handling</h2>
Assume that dates are in YYYY-MM-DD or MM-DD format. JavaScript can parse dates in that format using <em>new Date(datestr)</em>, but it is actually <strong>not recommended</strong> to use that mechanism (in the official documentation!) because it always assumes UTC if the timezone is not specified. That’s rather annoying and can be quite confusing. So don’t use the obvious thing. Sorry.

&nbsp;

Instead, here are a couple of options:

<ul>
<li>Use a regular expression (works well, maybe a little more complicated), or</li>
<li>Split on hyphens and use the numbers in each part that comes back.</li>
</ul>
&nbsp;

I opted for the second one for this example. Here’s a YYYY-MM-DD example:

<table>
<tbody>
<tr>
<td width="624">const [y, m, d] = datestr.split(‘-‘);

const date = new Date(+y, m-1, +d);</td>
</tr>
</tbody>
</table>
&nbsp;

Note that this only really works properly because “07” is the same as “7” in octal, and “08” is obviously not octal so it is interpreted as decimal. Therefore, it <em>does work</em> for all dates we care about, since we are guaranteed to not go above two digits, and once we get to two digits we never have a leading zero.

&nbsp;

<em>That said</em>, if you try to do this with years far in the past, it will <em>not work properly</em> because it will treat something like ‘0100’ not as year 100 AD, but as year 64 AD. Octal is fun.

&nbsp;

A more correct approach to getting integer values from JavaScript would be this:

<table>
<tbody>
<tr>
<td width="624">function parseDate(datestr) {

const [y, m, d] = datestr.split(‘-‘);

return new Date(Number.parseInt(y), Number.parseInt(m)-1, Number.parseInt(d));

}</td>
</tr>
</tbody>
</table>
&nbsp;

That gets you a time set to midnight of the given day (00:00:00, the very beginning of that day).

&nbsp;

To get today’s date and the current time, you can just do <em>const now = new Date()</em>.

&nbsp;

Note that, if you have to do sorting, you can easily treat a JavaScript date as a number by using the unary + operator. So, if you have the string “500”, you can make it act like a number by saying +”500”, for example.

&nbsp;

With dates, you can do this to get the number of seconds from now until a given “date”:

<table>
<tbody>
<tr>
<td width="624">let seconds = Math.floor((+date – new Date()) / 1000);</td>
</tr>
</tbody>
</table>
&nbsp;

The <em>new Date()</em> part doesn’t need a leading + because the subtraction operator also coerces the right side into a number.

&nbsp;

Note that once you have this “distance in seconds”, you also know whether the date is in the future or the past by looking at the sign of the result.

&nbsp;

Think about how, given the number of total seconds, you might create a nice countdown timer display with days, hours, minutes, and seconds remaining. You can use <em>Math.floor</em> as shown above, and you can also make use of the modulus operator %.

<h2>Form Submission</h2>
To create form elements that allow you to create a new event, here is one approach. Note carefully the <strong><em>onsubmit</em></strong> attribute. Also note that newlines get converted to spaces; you need to use HTML tags to indicate a new line or paragraph if you want that:

<table>
<tbody>
<tr>
<td width="624">&lt;form onsubmit=”return false”&gt;

Event name: &lt;input type=”text” id=”nameInput”&gt;

date: &lt;input type=”text” id=”dateInput”&gt;

&lt;button onclick=”createEvent()”&gt;create&lt;/button&gt;

&lt;/form&gt;
</td>
</tr>
</tbody>
</table>
&nbsp;

This will produce a form that you can fill out to create an element. You’ll need to write the `createEvent` function, which will find the `nameInput` and `dateInput` nodes, get their values, package them into JSON, and POST to /event.

&nbsp;

To find the date node and get its text, you might have code somewhere like this, in JavaScript:

<table>
<tbody>
<tr>
<td width="624">const dateStr = document.getElementById(‘dateInput’).value</td>
</tr>
</tbody>
</table>
&nbsp;

Again, note that the <em>onsubmit</em> for the form is important. Without that, your page will always be reloaded when the button is pressed, which makes debugging super hard (that bit me when I was writing up this example, and trying to figure *that* out while tired was… less successful than I would have liked).

&nbsp;

That reminds me, you can make debugging easier even with “Preserve Log” checked in the network tab in the Chrome developer tools; that at least allows you to see what happened across requests.

<a href="#_ftnref1" name="_ftn1"><sup>[1]</sup></a> You <strong>can</strong> use a framework like Angular or React if you want, but 1) you’ll be on your own, and 2) you <strong>cannot</strong> use a framework in a way that blurs the distinction between server and client, as many try to do. Keep that part crisp. Everything else is up to you.

<a href="#_ftnref2" name="_ftn2"><sup>[2]</sup></a> This is not an arbitrary requirement. First, it’s the way that many apps are done these days, and second, it paves the way for some important stuff when we augment this in later assignments.

<a href="#_ftnref3" name="_ftn3"><sup>[3]</sup></a> We need to have some way to mutate our data, after all! And we’ll be talking about some of the ramifications of using POST to modify potentially sensitive data and how to get around them.

<a href="#_ftnref4" name="_ftn4"><sup>[4]</sup></a> AppEngine is also “serverless” because you don’t think about things in terms of servers; you think of them in terms of events coming into your functions. AppEngine happens to be just enough richer that the barrier to entry is far lower than with functional approaches.

<a href="#_ftnref5" name="_ftn5"><sup>[5]</sup></a> Functions, Platform, or Infrastructure as a service. Lambda is a FaaS, AppEngine is a PaaS, and a virtual server that you have total control over would be an IaaS.

<a href="#_ftnref6" name="_ftn6"><sup>[6]</sup></a> You can, as mentioned earlier, use AWS Lambda or other technologies, but the setup there is nontrivial (involving S3 for static storage, an API gateway, CORS-enabled web pages, and several IAM roles to manage, with various attached policies on top of it all), so if you want to do that, you should assume you are mostly on your own.

&nbsp;

I can help you with just about any technology you choose, but my main focus will be on helping people who are just starting out, which means I’ll be expecting most folks to use the path of least resistance, and that’s Google AppEngine at the moment.

<a href="#_ftnref7" name="_ftn7"><sup>[7]</sup></a> &nbsp;The <em>reqJSON</em> function is provided here as a convenience if you want it. I use a promise-based implementation here, but that’s not required. If you know how to use the <em>XMLHttpRequest</em> you can just use it directly, for example. Or you can use the <em>fetch</em> API.

<a href="#_ftnref8" name="_ftn8"><sup>[8]</sup></a> Python 2 users will often use a library called “ndb”.
