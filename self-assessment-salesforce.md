---
layout: page
title: get a FREE org self-assessment tool
subtitle: Take this simple self-assessment tool to see how well you have implemented your Salesforce org.
cover-img: assets/img/main-header.png 
---

## Need help optimsing?
Ensure you have the best possible implementation of your Salesforce org.

Download this tool and assess your org - it's a great start to see where you're at with your Salesforce journey.


<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
<!--  If necessary, please modify the charset parameter to specify the        -->
<!--  character set of your HTML page.                                        -->
<!--  ----------------------------------------------------------------------  -->

<META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">
<script src="https://www.google.com/recaptcha/api.js"></script>
<script>
 function timestamp() { var response = document.getElementById("g-recaptcha-response"); if (response == null || response.value.trim() == "") {var elems = JSON.parse(document.getElementsByName("captcha_settings")[0].value);elems["ts"] = JSON.stringify(new Date().getTime());document.getElementsByName("captcha_settings")[0].value = JSON.stringify(elems); } } setInterval(timestamp, 500); 
</script>

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <FORM> element to your page.             -->
<!--  ----------------------------------------------------------------------  -->

<form action="https://webto.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">

<input type=hidden name='captcha_settings' value='{"keyname":"ContactPageKey","fallback":"true","orgId":"00D2w000007PAtA","ts":""}'>
<input type=hidden name="oid" value="00D2w000007PAtA">
<input type=hidden name="retURL" value="https://aocollab.tech/self-assessment-form-submitted/">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail" value="kate@aocollab.tech">      -->
<!--  ----------------------------------------------------------------------  -->

<label for="first_name">First Name</label><input  id="first_name" maxlength="40" name="first_name" size="20" type="text" /><br>

<label for="last_name">Last Name</label><input  id="last_name" maxlength="80" name="last_name" size="20" type="text" /><br>

<label for="email">Email</label><input  id="email" maxlength="80" name="email" size="20" type="text" /><br>

<label for="url">Website</label><input  id="url" maxlength="80" name="url" size="20" type="text" /><br>

<label for="company">Company</label><input  id="company" maxlength="40" name="company" size="20" type="text" /><br>

<label for="city">City</label><input  id="city" maxlength="40" name="city" size="20" type="text" /><br>

<div class="g-recaptcha" data-sitekey="6LcVXSsaAAAAAJLsAXEjmr1vvxy8xUyQzgwE9Wqm"></div><br>
<input type="submit" name="submit">

</form>

We're committed to your privacy. Ao Collaboration uses the information you provide to us to contact you about our relevant content, products, and services. You may unsubscribe from these communications at any time. For more information, check out our [Privacy Policy](https://aocollab.tech/privacypolicy/).
