# Roof-Rack-Drag
This website is designed to calculate the drag from a roof rack.
<style type="text/css">.box {
	color: #F90;
	background-color: #09F;
	border-top-color: #000;
	border-right-color: #000;
	border-bottom-color: #000;
	border-left-color: #000;
}
</style>
<form name="calculator">
<p>&nbsp;</p>

<p>Enter your transfer rate in <strong>kilobytes per second</strong> using the blue form below</p>

<p>The final amount transferred in GB is&nbsp;shown in the box&nbsp;below.</p>

<p>You must retype the upload rate number after each calculation in order to proceed with another one if you are doing multiple calculations.</p>

<p><input class="box" name="ans" type="textfield" /></p>

<p><br />
<input type="reset" value="Reset" /> <input onclick="document.calculator.ans.value=eval(document.calculator.ans.value *(60*60*24*31)/1024/1024)" type="button" value="Press to Calculate Monthly Transfer Rate in Gigabytes" /> <input onclick="document.calculator.ans.value=eval(document.calculator.ans.value *(60*60*24)/1024/1024)" type="button" value="Press to Calculate Daily Transfer Rate in Gigabytes" /> <input onclick="document.calculator.ans.value=eval(document.calculator.ans.value *(60*60)/1024/1024)" type="button" value="Press to Calculate Hourly Transfer Rate in Gigabytes" /> <input onclick="document.calculator.ans.value=eval(document.calculator.ans.value *(60)/1024/1024)" type="button" value="Press to Calculate Minutely Transfer Rate in Gigabytes" /></p>
</form>

