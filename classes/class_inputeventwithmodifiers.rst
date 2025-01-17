:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/InputEventWithModifiers.xml.

.. _class_InputEventWithModifiers:

InputEventWithModifiers
=======================

**Inherits:** :ref:`InputEventFromWindow<class_InputEventFromWindow>` **<** :ref:`InputEvent<class_InputEvent>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

**Inherited By:** :ref:`InputEventGesture<class_InputEventGesture>`, :ref:`InputEventKey<class_InputEventKey>`, :ref:`InputEventMouse<class_InputEventMouse>`

Base class for keys events with modifiers.

Description
-----------

Contains keys events information with modifiers support like :kbd:`Shift` or :kbd:`Alt`. See :ref:`Node._input<class_Node_method__input>`.

Tutorials
---------

- :doc:`InputEvent <../tutorials/inputs/inputevent>`

Properties
----------

+-------------------------+----------------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`alt_pressed<class_InputEventWithModifiers_property_alt_pressed>`                                   | ``false`` |
+-------------------------+----------------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`command_or_control_autoremap<class_InputEventWithModifiers_property_command_or_control_autoremap>` | ``false`` |
+-------------------------+----------------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`ctrl_pressed<class_InputEventWithModifiers_property_ctrl_pressed>`                                 | ``false`` |
+-------------------------+----------------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`meta_pressed<class_InputEventWithModifiers_property_meta_pressed>`                                 | ``false`` |
+-------------------------+----------------------------------------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>` | :ref:`shift_pressed<class_InputEventWithModifiers_property_shift_pressed>`                               | ``false`` |
+-------------------------+----------------------------------------------------------------------------------------------------------+-----------+

Methods
-------

+-------------------------+------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>` | :ref:`is_command_or_control_pressed<class_InputEventWithModifiers_method_is_command_or_control_pressed>` **(** **)** |const| |
+-------------------------+------------------------------------------------------------------------------------------------------------------------------+

Property Descriptions
---------------------

.. _class_InputEventWithModifiers_property_alt_pressed:

- :ref:`bool<class_bool>` **alt_pressed**

+-----------+------------------------+
| *Default* | ``false``              |
+-----------+------------------------+
| *Setter*  | set_alt_pressed(value) |
+-----------+------------------------+
| *Getter*  | is_alt_pressed()       |
+-----------+------------------------+

State of the :kbd:`Alt` modifier.

----

.. _class_InputEventWithModifiers_property_command_or_control_autoremap:

- :ref:`bool<class_bool>` **command_or_control_autoremap**

+-----------+-----------------------------------------+
| *Default* | ``false``                               |
+-----------+-----------------------------------------+
| *Setter*  | set_command_or_control_autoremap(value) |
+-----------+-----------------------------------------+
| *Getter*  | is_command_or_control_autoremap()       |
+-----------+-----------------------------------------+

Automaticaly use :kbd:`Meta` (:kbd:`Command`) on macOS and :kbd:`Ctrl` on other platforms. If ``true``, :ref:`ctrl_pressed<class_InputEventWithModifiers_property_ctrl_pressed>` and :ref:`meta_pressed<class_InputEventWithModifiers_property_meta_pressed>` cannot be set.

----

.. _class_InputEventWithModifiers_property_ctrl_pressed:

- :ref:`bool<class_bool>` **ctrl_pressed**

+-----------+-------------------------+
| *Default* | ``false``               |
+-----------+-------------------------+
| *Setter*  | set_ctrl_pressed(value) |
+-----------+-------------------------+
| *Getter*  | is_ctrl_pressed()       |
+-----------+-------------------------+

State of the :kbd:`Ctrl` modifier.

----

.. _class_InputEventWithModifiers_property_meta_pressed:

- :ref:`bool<class_bool>` **meta_pressed**

+-----------+-------------------------+
| *Default* | ``false``               |
+-----------+-------------------------+
| *Setter*  | set_meta_pressed(value) |
+-----------+-------------------------+
| *Getter*  | is_meta_pressed()       |
+-----------+-------------------------+

State of the :kbd:`Meta` modifier. On Windows and Linux, this represents the Windows key (sometimes called "meta" or "super" on Linux). On macOS, this represents the Command key.

----

.. _class_InputEventWithModifiers_property_shift_pressed:

- :ref:`bool<class_bool>` **shift_pressed**

+-----------+--------------------------+
| *Default* | ``false``                |
+-----------+--------------------------+
| *Setter*  | set_shift_pressed(value) |
+-----------+--------------------------+
| *Getter*  | is_shift_pressed()       |
+-----------+--------------------------+

State of the :kbd:`Shift` modifier.

Method Descriptions
-------------------

.. _class_InputEventWithModifiers_method_is_command_or_control_pressed:

- :ref:`bool<class_bool>` **is_command_or_control_pressed** **(** **)** |const|

On macOS, returns ``true`` if :kbd:`Meta` (:kbd:`Command`) is pressed.

On other platforms, returns ``true`` if :kbd:`Ctrl` is pressed.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
