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



#bHow does the plugin work?

The password strength algorithm is quite basic. It keeps track of a score that increases when a user uses certain characters in their password. By default, you can configure by how much the score increases for ...

* each character,
* each space,
* the usage of at least one lowercase character,
* the usage of at least one uppercase character,
* the usage of at least one number, and
* the usage of at least one symbol.

