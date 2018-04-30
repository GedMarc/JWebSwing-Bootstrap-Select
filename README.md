# JWebMP-Bootstrap-Select

Use Bootstrap Select directly in JWebMP

Example for simple drop down : 
```
BootstrapSelect bs = new BootstrapSelect();
bs.add(new Option("Option 1"));
bs.getOptions().setActionsBox(true);
```

As a feature on any component :
```
BootstrapSelectFeature bsf = new BootstrapSelectFeature(getInstance().getBody());
bsf.getOptions().setIconBase("fa fa-bell-o");
System.out.println(bsf.renderJavascript());
```

# Bootstrap Select

Bootstrap-select is a jQuery plugin that utilizes Bootstrap's dropdown.js to style and bring additional functionality to standard select elements.

Bootstrap Link
https://silviomoreto.github.io/bootstrap-select/

