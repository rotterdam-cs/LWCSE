LWCSE: Liferay Web Content Structure Enhancements
=================================================

This project (Liferay Hook) provides extra fields to the Liferay Web Content Structures.

The hook adds the following fields to the Liferay Web Content Structure:

* Time
* Date

Structure XML example:

<pre>
&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;root&gt;
   &lt;!-- Example event structure --&gt;
   &lt;!-- Title is inherited from Web Content --&gt;
   &lt;dynamic-element name="location" type="text" repeatable="true"/&gt;
   &lt;dynamic-element name="body" type="text_box" repeatable="true"/&gt;
   &lt;dynamic-element name="day" type="date" repeatable="true"/&gt;
   &lt;dynamic-element name="at" type="time" repeatable="true"/&gt;
&lt;/root&gt;
</pre>



Compatible with Liferay versions 6.1.x.
