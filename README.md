DURATION
========

[![NPM](https://nodei.co/npm/mpm.duration.png?downloads=true)](https://nodei.co/npm/mpm.duration/)

####author mparaiso <mparaiso@online.fr>

license: MIT

Deals with ISO 8601 durations.

<h3>Install</h3>
<h4>With npm</h4>
in package.json
<pre><code>
{
	"dependencies":{
		"mpm.duration":"*"
	}
}
</code></pre>

<h3>Usage</h3>

<p>Parse a String , get duration object</p>
<pre><code>
	var d1 = duration.parse("P1Y3M10D");
	assert(d.years==1);
	assert(d.months==3);
	assert(d.days==10);
</code></pre>
<p>Create a duration object in an object oriented way</p>
<pre><code>
	var d2 = new duration.Duration("PT3H10M4.05S");
	assert(d.hours==3);
	assert(d.minutes==10);
	assert(d.seconds==4.05);
</code></pre>
<p>Get a ISO duration string from a Duration object</p>
<pre><code>
	var d = new duration.Duration();
	d.years=5,d.months=4,d.hours=10;
	assert(d.toString()=="P5Y4MT10H");
</code></pre>