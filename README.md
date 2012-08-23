jQuery.onmValidate plugin
===================

Created by Fran Dieguez (http://mabishu.com / http://openhost.es)
Released under the MIT license.
More information at http://opensource.org/licenses/MIT

jQuery.onmValidate is a jQuery plugin that allows to validate HTML forms which are using the Twitter Boostrap (http://twitter.github.com/bootstrap/base-css.html#forms) form markup.
As the underlying Form validator this plugin uses the jQuery Tools Form component (http://jquerytools.org/documentation/validator/index.html).

#### Example

```javascript
$('#form').onmValidate();
```

```html
<form class="form-horizontal">
    <div class="control-group">
        <label class="control-label" for="inputEmail">Email</label>
        <div class="controls">
            <input type="email" id="inputEmail" placeholder="Email" required="required">
        </div>
    </div>
    <div class="control-group">
        <label class="control-label" for="inputPassword">Password</label>
        <div class="controls">
            <input type="password" id="inputPassword" placeholder="Password" required="required">
        </div>
    </div>
    <div class="input-prepend">
      <span class="add-on">@</span><input class="span2" id="prependedInput" size="16" type="text" placeholder="Username">
    </div>
</form>
```


Multilanguage
-------------------

If you have multiple languages enabled in jQuery Tools Validator plugin.
You can specify the language within this plugin.

```javascript
$('#form').onmValidate({
    'lang' : 'gl'
});
```