# jQuery.passwordStrength
`jQuery.passwordStrength` is a small jQuery plugin that visualizes the strength of a password entered into an input field.


# Example Usage

Using `jQuery.passwordStrength` is fairly simple — you only need to call a single method on the password field you want the plugin to monitor.

```html

<form action="#" method="get">
    <input type="password" id="password" />
</form>

<script type="text/javascript">
    $(function() {
        $("#password").passwordStrength();
    });
</script>


```
