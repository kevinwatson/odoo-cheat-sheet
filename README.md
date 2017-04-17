# Odoo Cheat Sheet

## Views

- Many to many and one to many fields rendered as many 2 many views by default will allow the user to delete the child record. To change this behavior and only allow users to remove the association rather than delete the record, set the following option:

```
<field name="one2many_field_name" options="{'not_delete': True}" />
```

[Source](http://stackoverflow.com/a/43414801)
