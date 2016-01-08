To make it work place ThousandSeparatorNumber.js file in some/package folder and write requires statement in some application initialization point E.g.

Ext.define('your.Application', {
    extend: 'Ext.app.Application',
  requires: ['some.package.ThousandSeparatorNumber']
});
