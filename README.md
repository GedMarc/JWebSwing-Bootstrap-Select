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


### Teamcity (https://jwebmp.com/teamcity/viewType.html?buildTypeId=JWebSwingPlugins_BuildBootstrapSelect)
### Jira https://jwebmp/jira/secure/RapidBoard.jspa?rapidView=1&projectKey=JWEB&view=planning.nodetail&epics=visible&selectedEpic=JWEB-186)
### SonarQube (https://jwebmp.com/sonar/dashboard?id=com.jwebmp%3Ajwebmp-bootstrap-select&did=1)
### Plugin Source (https://www.npmjs.com/package/bootstrap-select)

### Built in collobaration with 
![alt BrowserStack](https://bstacksupport.zendesk.com/attachments/token/ZbwSzMlt8HaSgOBgmGVHtpTNV/?name=Logo-01.svg)
