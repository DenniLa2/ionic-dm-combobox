ionic-combobox
==============

This directive add modal-combobox for select from the list or add new element.

installation
------------

    $ bower install ionic-combobox
    
in index.html add:

    <script src="lib/ionic-combo-box/combo-box.js"></script>

in app.js:

    angular.module('getFace', ['ionic', 'comboBoxDirective'])    
    
Usage
-----

    <div ng-model="selectedItem"
        combo-box="prepopulatedItemsArray"
        cbx-placeholder="Item"
        cbx-filter-caption="used items:"
        cbxEmptyFilterCaption="No items found"
        cbx-close-on-select></div>
      
    