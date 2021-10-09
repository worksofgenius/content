---
title: <msubsup>
slug: Web/MathML/Element/msubsup
tags:
  - MathML
  - MathML Reference
  - MathML:Element
  - MathML:Script and Limit Schemata
browser-compat: mathml.elements.msubsup
---
<div>{{MathMLRef}}</div>

<p><span class="seoSummary">The MathML <code>&lt;msubsup&gt;</code> element is used to attach both a subscript and a superscript, together, to an expression.</span></p>

<p>It uses the following syntax: <code>&lt;msubsup&gt; <em>base subscript superscript</em> &lt;/msubsup&gt;</code>.</p>

<h2 id="Attributes">Attributes</h2>

<dl>
 <dt id="attr-class-id-style"><code>class</code>, <code>id</code>, <code>style</code></dt>
 <dd>Provided for use with <a href="/en-US/docs/Web/CSS">stylesheets</a>.</dd>
 <dt id="attr-displaystyle"><code>displaystyle</code></dt>
 <dd>A Boolean value specifying whether more vertical space is used for displayed equations or, if set to <code>false</code>, a more compact layout is used to display formulas. The main effect is that larger versions of operators are displayed, when <code>displaystyle</code> is set to <code>true</code>. See also <code>movablelimits</code> on {{ MathMLElement("mo") }}.</dd>
 <dt id="attr-href"><code>href</code></dt>
 <dd>Used to set a hyperlink to a specified URI.</dd>
 <dt id="attr-mathbackground"><code>mathbackground</code></dt>
 <dd>The background color. You can use <code>#rgb</code>, <code>#rrggbb</code> and <a href="/en-US/docs/Web/CSS/color_value#color_keywords">HTML color names</a>.</dd>
 <dt id="attr-mathcolor"><code>mathcolor</code></dt>
 <dd>The text color. You can use <code>#rgb</code>, <code>#rrggbb</code> and <a href="/en-US/docs/Web/CSS/color_value#color_keywords">HTML color names</a>.</dd>
 <dt id="attr-subscriptshift"><code>subscriptshift</code> {{deprecated_inline}}</dt>
 <dd>The minimum space by which to shift the subscript below the baseline of the expression, as a <a href="/en-US/docs/Web/MathML/Attribute/Values#lengths">length value.</a><br>
 This attribute is deprecated and will be removed in the future.</dd>
 <dt id="attr-superscriptshift"><code>superscriptshift</code> {{deprecated_inline}}</dt>
 <dd>The minimum space by which to shift the superscript above the baseline of the expression, as a <a href="/en-US/docs/Web/MathML/Attribute/Values#lengths">length value.</a><br>
 This attribute is deprecated and will be removed in the future.</dd>
</dl>

<h2 id="Examples">Examples</h2>

<p>Sample rendering: <img alt="x1" src="msubsup.png"></p>

<p>Rendering in your browser: <math> <msubsup> <mo> ∫</mo> <mn> 0 </mn> <mn> 1 </mn> </msubsup> </math></p>

<pre class="brush: html">&lt;math displaystyle="true"&gt;

  &lt;msubsup&gt;
    &lt;mo&gt; &amp;#x222B;&lt;!--Integral --&gt; &lt;/mo&gt;
    &lt;mn&gt; 0 &lt;/mn&gt;
    &lt;mn&gt; 1 &lt;/mn&gt;
  &lt;/msubsup&gt;

&lt;/math&gt;
</pre>

<h2 id="Specifications">Specifications</h2>

<p>{{Specifications}}</p>

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>

<h2 id="See_also">See also</h2>

<ul>
 <li>{{ MathMLElement("msub") }} (Subscript)</li>
 <li>{{ MathMLElement("msup") }} (Superscript)</li>
 <li>{{ MathMLElement("mmultiscripts") }} (Prescripts and tensor indices)</li>
</ul>