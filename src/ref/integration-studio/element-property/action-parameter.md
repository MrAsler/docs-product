# Action Parameter Properties

The next table presents the properties of the [action parameter](<../../../extensibility-and-integration/integration-studio/managing-extensions/action-parameter.md>) element.  
  
<table markdown="1">  
<tr>
<th>
Property
</th>
<th>
Description
</th>
<th>
Optionality
</th>
<th>
Default value
</th>
<th>
Obs.
</th>
</tr>
<tr>
<td>
Name
</td>
<td>
Name of the parameter.
</td>
<td>
Mandatory
</td>
<td>
`Parameter <n>`
</td>
<td>
You should change the name of the parameter to a suitable value.
See [rules for naming elements](<../element-naming.md>).
</td>
</tr>
<tr>
<td>
Input
</td>
<td>
Indicates whether the parameter is an input or output parameter.
</td>
<td>
Mandatory
</td>
<td>
`Input`
</td>
<td>
See how to [change the type of the parameter](<../editor/action-parameters.md>).
</td>
</tr>
<tr>
<td>
Mandatory
</td>
<td>
Indicates whether the input parameter is mandatory or optional.
</td>
<td>
Mandatory
</td>
<td>
`Mandatory`
</td>
<td>
To define an input parameter as optional simply un-check this property.
</td>
</tr>
<tr>
<td>
Data Type
</td>
<td>
Indicates the type of the parameter. You can use basic data types such as Text or Integer; or you might need more complex data types to handle this parameter. Integration Studio provides the **Record** and **Record List** data types. The definitions of the **Record** and **Record List** data types are based on the [structures](<../../../extensibility-and-integration/integration-studio/managing-extensions/structure-define.md>) and [entities](<../../../extensibility-and-integration/integration-studio/managing-extensions/entity-define.md>) available in your extension.
</td>
<td>
Mandatory
</td>
<td>
</td>
<td>
The possible values are presented in a drop-down list. For more information, see available data types.
Since OutSystems has its own data types, you should check how these data types are translated into Microsoft .NET data types.
</td>
</tr>
<tr>
<td>
Default value
</td>
<td>
Default value that is used if no value for this parameter is provided in the module that is using this action.
</td>
<td>
Optional
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td>
Record Type
</td>
<td>
If your parameter data type is a Record or a Record List, you have to select the [entities](<../../../extensibility-and-integration/integration-studio/managing-extensions/entity-add.md>) and/or [structures](<../../../extensibility-and-integration/integration-studio/managing-extensions/structure-define.md>) that define the Record or Record List. Learn more about these data types.
The value of this property is the name of the entity or structure. In case you have a combination of both entities and/or structures, the value is (Join).
</td>
<td>
Optional
</td>
<td>
</td>
<td>
Mandatory only if the **Data Type** is `Record` or `Record List`.
</td>
</tr>
<tr>
<td>
Description
</td>
<td>
Description of the parameter.
</td>
<td>
Optional
</td>
<td>
</td>
<td>
By default the description is empty, but you should provide a small description of the semantic of this parameter. The maximum allowed size for descriptions is 255 characters.
</td>
</tr>
</table>
