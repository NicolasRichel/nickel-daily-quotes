# \<nickel-daily-quotes\>
(Built with Polymer 2.0)

A simple and customizable message display.  
Given a list of messages (quotes) the `<nickel-daily-quotes>` element will successively
display each message by switching the displayed message at regular interval.
It uses the [`<nickel-timer>`]() element to handle time based trigger.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="./nickel-daily-quotes.html"/>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<nickel-daily-quotes period="2">
  <ul>
    <li>Msg 1</li>
    <li>Msg 2</li>
    <li>Msg 3</li>
  </ul>
</nickel-daily-quotes>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

GNU General Public License version 3.0.
