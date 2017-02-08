<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../iron-demo-helpers/demo-pages-shared-styles.html">
    <link rel="import" href="../iron-demo-helpers/demo-snippet.html">
    <link rel="import" href="sched-datepicker.html">
    <style is="custom-style" include="demo-pages-shared-styles"></style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<sched-datepicker></sched-datepicker>
```

### yet another datepicker (a prototype for sched.site)

features:
  - today button 
  - min & max dates 
  - select from an array of available dates
  - multi date picker (select multiple dates)
  - date range picker (select two dates: start & end)

note: 
  - multidate & rangedate can't be used at the same time! 
  

## API DOC, DEMO, & TEST PAGES

API DOC & DEMO: https://edwardsharp.github.io/sched-datepicker/

DEMO: https://edwardsharp.github.io/sched-datepicker/components/sched-datepicker/demo/index.html

TESTS: https://edwardsharp.github.io/sched-datepicker/components/sched-datepicker/test/sched-datepicker_test.html

## INSTALL 

```
bower i edwardsharp/sched-datepicker -S
```

## TESTING

```
$ polymer test
```

...or visit  /components/sched-datepicker/test/sched-datepicker_test.html  (e.g. http://localhost:8080/components/sched-datepicker/test/sched-datepicker_test.html)

## problems? feature requests?

create an issue.