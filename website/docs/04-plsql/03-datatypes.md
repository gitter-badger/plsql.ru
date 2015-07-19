---
layout: page
title: Типы данных (DATATYPES)
permalink: /docs/plsql/datatypes/
---


### Типы данных (DATATYPES)


Все переменные PL/SQL имеют тип данных, определяющий формат хранения, ограничения и диапазон допустимых значения.<br/><br/>
PL/SQL поддерживает 5 категорий типов данных:<br/><br/>

<ul>
<li>Скалярные типы данных (Scalar) – содержат одно значение. Значение зависит от типа данных переменной. </li>
<li>Составные типы  (Composite) – содержат внутренние элементы, которые могут быть скалярного или составного типов. К ним относятся записи и таблицы PL/SQL.</li>
<li>Ссылочные типы данных (Reference) – содержат значения, называемые указателями (Pointers), указывающие на другие места хранения.</li>
<li>Типы данных LOB (Large object (LOB)) – содержат так называемые указатели места (locators), указывающие местоположение больших объектов (например, графических образов)), которые хранятся отдельно от других столбцов строки (out of line).</li>
</ul>