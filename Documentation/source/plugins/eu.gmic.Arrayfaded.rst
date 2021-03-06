.. _eu.gmic.Arrayfaded:

G’MIC Array faded node
======================

*This documentation is for version 1.0 of G’MIC Array faded.*

Description
-----------

Wrapper for the G’MIC framework (http://gmic.eu) written by Tobias Fleischer (http://www.reduxfx.com) and Frederic Devernay.

Inputs
------

+--------+-------------+----------+
| Input  | Description | Optional |
+========+=============+==========+
| Source |             | No       |
+--------+-------------+----------+

Controls
--------

.. tabularcolumns:: |>{\raggedright}p{0.2\columnwidth}|>{\raggedright}p{0.06\columnwidth}|>{\raggedright}p{0.07\columnwidth}|p{0.63\columnwidth}|

.. cssclass:: longtable

+--------------------------------------------+---------+---------+----------------------------------+
| Parameter / script name                    | Type    | Default | Function                         |
+============================================+=========+=========+==================================+
| X-tiles / ``Xtiles``                       | Integer | 2       |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Y-tiles / ``Ytiles``                       | Integer | 2       |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| X-offset (%) / ``Xoffset_``                | Double  | 0       |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Y-offset (%) / ``Yoffset_``                | Double  | 0       |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Fade start (%) / ``Fade_start_``           | Double  | 80      |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Fade end (%) / ``Fade_end_``               | Double  | 90      |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Mirror / ``Mirror``                        | Choice  | None    | |                                |
|                                            |         |         | | **None**                       |
|                                            |         |         | | **x-axis**                     |
|                                            |         |         | | **y-axis**                     |
|                                            |         |         | | **xy-axes**                    |
+--------------------------------------------+---------+---------+----------------------------------+
| Size / ``Size``                            | Choice  | Shrink  | |                                |
|                                            |         |         | | **Shrink**                     |
|                                            |         |         | | **Expand**                     |
|                                            |         |         | | **Repeat [Memory consuming!]** |
+--------------------------------------------+---------+---------+----------------------------------+
| Output Layer / ``Output_Layer``            | Choice  | Layer 0 | |                                |
|                                            |         |         | | **Merged**                     |
|                                            |         |         | | **Layer 0**                    |
|                                            |         |         | | **Layer -1**                   |
|                                            |         |         | | **Layer -2**                   |
|                                            |         |         | | **Layer -3**                   |
|                                            |         |         | | **Layer -4**                   |
|                                            |         |         | | **Layer -5**                   |
|                                            |         |         | | **Layer -6**                   |
|                                            |         |         | | **Layer -7**                   |
|                                            |         |         | | **Layer -8**                   |
|                                            |         |         | | **Layer -9**                   |
+--------------------------------------------+---------+---------+----------------------------------+
| Resize Mode / ``Resize_Mode``              | Choice  | Dynamic | |                                |
|                                            |         |         | | **Fixed (Inplace)**            |
|                                            |         |         | | **Dynamic**                    |
|                                            |         |         | | **Downsample 1/2**             |
|                                            |         |         | | **Downsample 1/4**             |
|                                            |         |         | | **Downsample 1/8**             |
|                                            |         |         | | **Downsample 1/16**            |
+--------------------------------------------+---------+---------+----------------------------------+
| Ignore Alpha / ``Ignore_Alpha``            | Boolean | Off     |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Preview/Draft Mode / ``PreviewDraft_Mode`` | Boolean | Off     |                                  |
+--------------------------------------------+---------+---------+----------------------------------+
| Log Verbosity / ``Log_Verbosity``          | Choice  | Off     | |                                |
|                                            |         |         | | **Off**                        |
|                                            |         |         | | **Level 1**                    |
|                                            |         |         | | **Level 2**                    |
|                                            |         |         | | **Level 3**                    |
+--------------------------------------------+---------+---------+----------------------------------+
