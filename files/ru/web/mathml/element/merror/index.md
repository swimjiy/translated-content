---
title: <merror>
slug: Web/MathML/Element/merror
tags:
  - MathML
  - MathML Reference
  - 'MathML:Element'
  - 'MathML:General Layout Schemata'
translation_of: Web/MathML/Element/merror
---
<div>{{MathMLRef}}</div>

<p class="summary">Элемент MathML <code>&lt;merror&gt;</code> используется для отображения содержимого в виде сообщений об ошибках. В Firefox это сообщение об ошибке отображается аналогично типичному сообщению об ошибке XML. Обратите внимание, что эта ошибка <strong>не</strong> выдаётся, если ваша разметка MathML неверна или неправильно сформирован XML. Вы всё равно получите ошибку разбора XML (в случае XHTML-нотации MathML), которая не имеет ничего общего с <code>&lt;merror&gt;</code>.</p>

<h2 id="Атрибуты">Атрибуты</h2>

<dl>
 <dt id="attr-class-id-style">class, id, style</dt>
 <dd>Предполагается использование с <a href="/ru/docs/CSS">таблицами стилей</a>.</dd>
 <dt id="attr-href">href</dt>
 <dd>Используется для установки гиперссылки на указанный URI.</dd>
 <dt id="attr-mathbackground">mathbackground</dt>
 <dd>Цвет фона. Ты можешь использовать <code>#rgb</code>, <code>#rrggbb</code> и <a href="/ru/docs/CSS/color_value#Color_Keywords">имена цветов HTML</a>.</dd>
 <dt id="attr-mathcolor">mathcolor</dt>
 <dd>Цвет текста, а также цвет линии дроби. Вы можете использовать <code>#rgb</code>, <code>#rrggbb</code> и <a href="/ru/docs/CSS/color_value#Color_Keywords">имена цветов HTML</a>.</dd>
</dl>

<h2 id="Примеры">Примеры</h2>

<pre class="brush: html">&lt;math&gt;

&lt;merror&gt;
  &lt;mrow&gt;
    &lt;mtext&gt; Деление на ноль: &lt;/mtext&gt;
    &lt;mfrac&gt;
      &lt;mn&gt; 1 &lt;/mn&gt;
      &lt;mn&gt; 0 &lt;/mn&gt;
    &lt;/mfrac&gt;
  &lt;/mrow&gt;
&lt;/merror&gt;

&lt;/math&gt;
</pre>

<h2 id="Спецификации">Спецификации</h2>

{{Specifications}}

<h2 id="Совместимость_с_браузерами">Совместимость с браузерами</h2>

<p> </p>



<p>{{Compat}}</p>

<p> </p>