
Designing a PCB
================================

Main Menu
------------

.. glossary::

    File
        Recover Board --  recover the latest project version

    Edit    
        Edit Selection

    Placement
        * Arrange Components -- components will be arranged according to 
          the placement settings near the design center

    View
        * Component Markings -- set reference designators visibility
        * Units -- change the measurement units
        * Precision -- configure precision of all the values in the project
        * Origin -- see the origin point
        * Mirror -- see how the bottom layer actually looks like
        * Customize Grid -- configure the list of available grids
        * Display hint
            * Add Object Details -- display trace length

    Objects
        * Place Ratline --  create a pad-to-pad connections visually
        * Place Board Outline -- place the board outline on the design area
        * Board Points -- n Add, Insert and Delete key points
        * Delete Board -- delete the outline polygon
        * Place Static Via -- place several static vias

    Route
        * Connection Manager -- add, delete or rename nets, as well as add or 
          delete pads to/from the nets
        * Lock Net Structure -- protect the net structure from accidental change
        * Current Autorouter
            * Shape Router -- the best option for complex and simple designs 
            * Grid Router -- options for jumper wires
            * Run DRC after autorouting -- switch on design rules check
        * Autorouter Setup -- set up the autorouter
        * Route Setup -- the trace width and clearance between traces
        * Run Autorouter -- route the circuit board
        * Layer Setup -- add, edit, create or delete a layer
        * Via styles -- set via type and size
        * Manual Routing
            * Add Traces -- start routing
            * Edit Traces -- y left-click on the trace and drag it to another location and drop it
            * Free Trace Editing -- edit traces without any restrictions
        * Unroute All -- completely unroute nets
        * Net Classes

    Verification
        * Check Design Rules -- verifies object sizes, length/phase parameters o
          f highspeed nets, and clearances between different objects
        * Design Rules -- change design rules

HotKey
--------------

.. glossary::

    F10
        Optimize visual appearance of the connection lines

    F11 
        Hide/Show grid
    
    1
        Go to top layer

    2
        Go to bottom layer

    CTRL + F9
        Run Autorouter

    CTRL + Z
        undo last doing

    CTRL + '+'
        Encrease grid step

    CTRL + '-'
        Decrease grid step

    Left Click on trace + N    
        Add a new node in the selected place

    Tab
        toggle between the selection of a segment, a trace or the entire net
