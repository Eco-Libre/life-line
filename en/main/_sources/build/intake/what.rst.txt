.. _intake_what:

What is the "Intake" Component?
===============================

This section will describe how to build the "Intake" component of the Eco-Libre Life-Line system.

.. figure:: /images/life-line_intake_parts.svg
  :target: ../../_images/life-line_intake_parts.svg
  :align: center

  CAD Design of the Eco-Libre Life-Line's "Intake" component

.. note::
   Want to **view the 3D Model** of the Intake Compoenent above?

   You can download the ``intake.FCStd`` file from out `GitHub repo <github_repo_>`_ and open it on your computer in `FreeCAD <freecad_download_>`_

The "Intake" component is responsible for raw water capture from a stream. The design of >=20cm falling, turbulent water is self-cleaning: the turbulent water falls onto the screen with sufficient force to clear debris off of the screen. This ensures constant raw water collection into the Life-Line system, without requiring periodic manual human intervention (or automatic moving parts) needed to remove debris blocking the ingest of water into the system.

The "Intake" component is made-up of several parts:

.. _intake_weir:

1. Weir
-------

The Weir is a masonry structure (CEB, Concrete Block, or Steel-reinforced Concrete) that's built in the middle of a stream. It has a Weir Opening at the top, which channels falling water to flow ontop of a :ref:`metal screen <intake_screen>` and into a :ref:`water collection drum <intake_drum>`.

	* - .. figure:: /images/life-line_intake_weir.jpg
		:target: ../../_images/life-line_intake_weir.jpg
		:alt: Screenshot of FreeCAD, highlighting a long blue drum that's cut in half
		:align: center

		The Life-Line "Intake" component's Weir

	  - .. figure:: /images/life-line_praxis_boris-plotkin.2024-11.jpg
		:target: ../../_images/life-line_praxis_boris-plotkin.2024-11.jpg
		:alt: Photo of a freshly-constructed rock-and-concrete-block weir
		:align: center

		Concrete Block, Rock, and Cement Weir for the Eco-Libre Life-Line at Fruit Haven in Morona-Santiago, Ecuador (attribution: `Boris Plotkin <bplotkin_>`_)

The distance between the bottom of the Weir Opening and the top of the :ref:`Fine Mesh Screen <intake_screen>` atop the :ref:`water collection drum <intake_drum>` must be at least 20 cm. If the water falls less than 20 cm, it will not have enough force to self-clean the :ref:`screen <intake_screen>` of organic debris.

.. _intake_turbulence_bar:

2. Turbulence Bar
-----------------

The Turbulence Bar is a piece of steel angle that's bolted to the :ref:`weir <intake_weir>`, bisecting the Weir Opening.

.. figure:: /images/life-line_intake_turbulence-bar.jpg
  :align: center

  The Life-Line "Intake" component's Turbulence Bar

The Turbulence Bar changes the flow of the water as it passes through the Weir Opening, creating turbulence. This turbulant water is more effective at self-cleaning the :ref:`screen <intake_screen>` below of organic debris than non-turbulant falling water.

.. _intake_screen:

3. Fine Mesh Screen
-------------------

The Fine Mesh Screen is a very fine metal screen that's designed to filter-out large organic materials (eg leaves, sticks, stones, grass, etc) from entering the :ref:`drum <intake_drum>`.

.. figure:: /images/life-line_intake_fine-mesh.jpg
  :align: center

  The Life-Line "Intake" component's Fine Mesh Screen

The Fine Mesh Screen should be made of Stainless Steel, and the holes in the screen should be approximately 0.85 mm large (20 `US Mesh <20mesh_>`_)

.. _intake_expanded_metal:

4. Expanded Metal Mesh
----------------------

The Expanded Metal Mesh is a strong grate made of Expanded Metal that sits below the :ref:`Fine Mesh Screen <intake_screen>` and atop the Drum

.. figure:: /images/life-line_intake_expanded-metal.jpg
  :align: center

  The Life-Line "Intake" component's Expanded Metal Mesh

The purpose of the Expanded Metal Mesh is to provide a physical support structure for the :ref:`Fine Mesh Screen <intake_screen>` above it.

.. _intake_outflow_pipe:

5. Outflow Pipe
---------------

The Outflow Pipe is where water flows out of the Intake :ref:`drum <intake_drum>` and into the next component of the Eco-Libre Life-Line system (the :ref:`settling_tank` Component)

.. figure:: /images/life-line_intake_outflow.jpg
  :align: center

  The Life-Line "Intake" component's Outflow Pipe

The outflow pipe consists of a Bushing, Pipe, and Valve.

.. _intake_drain_pipe:

6. Cleanout Drain Pipe
----------------------

The Cleanout Drain Pipe is located at the bottom of the :ref:`drum <intake_drum>`, next to the :ref:`Outflow Pipe <intake_outflow_pipe>`.

.. figure:: /images/life-line_intake_cleanout-drain.jpg
  :align: center

  The Life-Line "Intake" component's Cleanout Drain Pipe

The Cleanout Drain Pipe consists of a Bushing, Pipe, and Valve.

The purpose of the Cleanout Drain Pipe is to flush small debris (eg sand) that have collected at the bottom of the drum. In normal operations, the valve should be closed. During routine maintenance (at least once per year), the Cleanout Drain Pipe should be opened, to flush-out any debris that have settled at the bottom of the drum.

If possible, a valve actuator (eg a simple electronic sprinkler system on a timer) could be placed after the valve to automatically flush the drum on a routine basis.

.. _intake_drum:

7. Drum
-------

The Drum is a standard 220L (55 gallon) HDPE barrel drum that's been cut in half length-wise.

.. figure:: /images/life-line_intake_drum.jpg
  :align: center

  The Life-Line "Intake" component's Drum

The drum collects water as it spills over the weir and onto the :ref:`metal mesh screen <intake_screen>` that sit atop the cut-open face of the drum.

Two holes are cut on the downstream side of the drum, where through-wall bushings are placed for the :ref:`Cleanout Drain Pipe <intake_drain_pipe>` and the :ref:`Outflow Pipe <intake_outflow_pipe>`.

.. _20mesh: https://en.wikipedia.org/wiki/Mesh_(scale)
.. _github_repo: https://github.com/eco-libre/life-line
.. _freecad_download: https://www.freecad.org/downloads
.. _bplotkin: https://t.me/borisplot
