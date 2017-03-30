# things-resource-selector

Example:

```html
        <things-resource-field
          id="resource-selector"
          label="Language"
          name="user_id"
          resource-type="User"
          resource-url="users"
          delegate-column="name">
        </things-resource-field>

```

*****
</br></br>





## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-alarm/`, where `things-alarm` is the name of the directory containing it.
