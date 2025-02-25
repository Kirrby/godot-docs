:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/VisualShaderNodeBooleanParameter.xml.

.. _class_VisualShaderNodeBooleanParameter:

VisualShaderNodeBooleanParameter
================================

**Inherits:** :ref:`VisualShaderNodeParameter<class_VisualShaderNodeParameter>` **<** :ref:`VisualShaderNode<class_VisualShaderNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

A boolean parameter to be used within the visual shader graph.

Description
-----------

Translated to ``uniform bool`` in the shader language.

Properties
----------

+-------------------------+-----------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`default_value<class_VisualShaderNodeBooleanParameter_property_default_value>`                 | ``false`` |
+-------------------------+-----------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`default_value_enabled<class_VisualShaderNodeBooleanParameter_property_default_value_enabled>` | ``false`` |
+-------------------------+-----------------------------------------------------------------------------------------------------+-----------+

Property Descriptions
---------------------

.. _class_VisualShaderNodeBooleanParameter_property_default_value:

- :ref:`bool<class_bool>` **default_value**

+-----------+--------------------------+
| *Default* | ``false``                |
+-----------+--------------------------+
| *Setter*  | set_default_value(value) |
+-----------+--------------------------+
| *Getter*  | get_default_value()      |
+-----------+--------------------------+

A default value to be assigned within the shader.

----

.. _class_VisualShaderNodeBooleanParameter_property_default_value_enabled:

- :ref:`bool<class_bool>` **default_value_enabled**

+-----------+----------------------------------+
| *Default* | ``false``                        |
+-----------+----------------------------------+
| *Setter*  | set_default_value_enabled(value) |
+-----------+----------------------------------+
| *Getter*  | is_default_value_enabled()       |
+-----------+----------------------------------+

Enables usage of the :ref:`default_value<class_VisualShaderNodeBooleanParameter_property_default_value>`.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
