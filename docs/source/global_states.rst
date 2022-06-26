.. _global_states:

Global States
=====================

Static Global States can be specified (to be created upon application creation).
A state is created with a Key and the associated value.

There are three forms of Global States that can be created with respect to their data types:

================================ ====================================================
Data Type                        Description
================================ ====================================================
Byte String                      Used to provide a value of ByteSlice that 
                                 should be stored in the state.
Integer                          Used to provide integral value that 
                                 should be stored in the state.
Address                          Used to provide a valid Algorand address that 
                                 should be stored in the state.
================================ ====================================================

Upon creation of the Application, the created Global States will be created for use in the rest of the application's lifetime.