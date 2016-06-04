Hi everyone

How to use of moneybox

Example:

Name : P6_SALARY
Type : NumberField

Custom Attributes :=
 onchange="valueChange('P6_SALARY');" onkeyup="contentKeyUp('P6_SALARY');" onblur="blurContent('P6_SALARY');" onfocus="focusContent('P6_SALARY');"

Pre Text:
<dl id="p6_salary_show_money" isrequired="True">
    <dt>


Post Text:
</dt>
    <dd>
        <ul id="p6_salary_show_money_text" style="display: none;"></ul>
    </dd>
    <dt>
        <label id="p6_salary_show_money_separated" style="display: block;"></label>
    </dt>
</dl>

