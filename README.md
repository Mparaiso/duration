DURATION
========

####author mparaiso <mparaiso@online.fr>

license: MIT

Deals with ISO durations.
<h3>Usage</h3>
<h5>author mparaiso : mparaiso@online.fr</h5>
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