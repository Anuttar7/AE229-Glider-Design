# AE229 Glider Report --- Team E

## Overview

This repository contains the report and design work for **AE229
Glider**, completed by **Team E**. The project focuses on designing,
testing, and evaluating lightweight gliders, with particular attention
to lift, drag, glide performance, stability, and practical flight
behaviour.

The team explored two glider designs:

-   **Glider #1** --- an airfoil-based design intended to improve lift
    and glide performance.
-   **Glider #2** --- a simplified design developed after evaluating the
    sensitivity and practical limitations of Glider #1.

The report includes design considerations, flight testing, wind-tunnel
measurements, lift-to-drag calculations, and a drag-polar analysis.
\[Report, pp. 1--10\]

## Team

  Name              Roll Number
  ----------------- -------------
  Sujal Machhale    22B0001
  Nikhil Acharya    22B0002
  Anuttar Jain      22B0003
  Rohan Chowdhury   22B0042

## Project Contents

The report is organized around the following topics:

1.  Glider #1 --- airfoil-based design
2.  Lift-to-drag (L/D) calculations
3.  Wind-tunnel testing
4.  Drawbacks of Glider #1
5.  Glider #2 --- simplified design
6.  Drag-polar analysis

## Glider #1

Glider #1 uses **SD7003 airfoils** for its wings to generate increased
lift. The fuselage was designed with a trapezoidal shape so that the
wings could be mounted with a **15° dihedral angle**, providing roll
stability.

Several practical design choices were made to improve stability and
performance:

-   Coins were placed near the nose to move the **centre of gravity (CG)
    forward**, helping maintain rotational equilibrium.
-   The horizontal stabilizers were mounted at a height on the vertical
    stabilizer so that they would encounter relatively streamlined flow
    rather than the turbulent wake produced by the wings.

These features and the physical prototype are shown in the report on
page 3. \[Report, p. 3\]

## Flight Testing and L/D Calculation

The report estimates the glide performance of Glider #1 using a flight
test.

The recorded values were:

  Parameter                                                                         Value
  ---------------------------------------------------------------------------- ----------
  Throw height                                                                        2 m
  Horizontal range                                                                 8.12 m
  Time taken                                                                          1 s
  Total distance travelled                                                         8.36 m
  Estimated speed                                                                8.36 m/s
  Glide angle                                                                      13.84°
  Calculated C`<sub>`{=html}L`</sub>`{=html}/C`<sub>`{=html}D`</sub>`{=html}     **4.06**

The horizontal range was obtained as 8.12 m, and the report uses:

\[ `\cot`{=tex}(`\phi`{=tex}) = `\frac{8.12}{2}`{=tex} = 4.06 \]

giving an estimated **lift-to-drag ratio of 4.06**. \[Report, p. 6\]

## Wind-Tunnel Testing

Glider #1 was also tested in a wind tunnel at different angles of
attack. The measured lift values were:

    Angle of Attack   Lift
  ----------------- ------
                -5°   15 g
                 0°   45 g
                 5°   65 g
                10°   76 g
                15°   74 g

The measurements show that lift increased with angle of attack up to
approximately **10°**, after which the measured lift decreased slightly
at **15°**. The corresponding experimental setup is shown on page 7 of
the report. \[Report, p. 7\]

## Limitations of Glider #1

Although the airfoil-based design increased lift, the report found that
the resulting glider was **highly sensitive to small imbalances**.

According to the flight experience documented in the report:

-   Even small imbalances produced large deviations from the intended
    flight path.
-   These deviations could eventually result in crash landings.
-   Because of this sensitivity, the team decided not to continue with
    the airfoil-based configuration and instead developed a simpler
    design.

This design decision is discussed on page 8. \[Report, p. 8\]

## Glider #2

Glider #2 was developed with the goal of achieving a design requiring
**less effort while remaining efficient**.

Key design features include:

-   Wings made from a **single piece of Depron**.
-   Wing edges were sanded to obtain an airfoil-like profile.
-   Horizontal stabilizers were placed at approximately the same level
    as the wings.
-   Small rectangular cuts were incorporated to allow adjustment of the
    **elevator angle** and experimentation with the optimal glide angle.
-   Coins were again placed near the nose for CG adjustment.
-   Approximate mass: **28 g**.

The physical design is shown on page 9 of the report. \[Report, p. 9\]

## Drag Polar

The final section of the report presents a drag-polar-style analysis
based on measured lift and drag coefficients.

  -----------------------------------------------------------------------------------------------------------------------------------------
                     Lift Coefficient                    Drag Coefficient   C`<sub>`{=html}L`</sub>`{=html}/C`<sub>`{=html}D`</sub>`{=html}
    (C`<sub>`{=html}L`</sub>`{=html})   (C`<sub>`{=html}D`</sub>`{=html}) 
  ----------------------------------- ----------------------------------- -----------------------------------------------------------------
                                 1.13                              0.2209                                                            5.1154

                                 1.38                              0.3011                                                            4.5832

                                 1.85                              0.4720                                                            3.9195

                                 2.37                              0.6968                                                            3.4013

                                 2.87                              0.9308                                                            3.0834
  -----------------------------------------------------------------------------------------------------------------------------------------

The plotted
**C`<sub>`{=html}L`</sub>`{=html}/C`<sub>`{=html}D`</sub>`{=html}**
values decrease as the lift coefficient increases over the measured
range. The graph and underlying table are provided on page 10 of the
report. \[Report, p. 10\]

## Key Results

The main experimental and design outcomes reported by the team are:

-   Glider #1 achieved an estimated
    **C`<sub>`{=html}L`</sub>`{=html}/C`<sub>`{=html}D`</sub>`{=html} of
    4.06** from the flight-test calculation.
-   Wind-tunnel testing showed increasing lift from **15 g at -5°** to
    **76 g at 10°**, followed by a slight reduction to **74 g at 15°**.
-   The airfoil-based configuration produced higher lift but was found
    to be sensitive to small imbalances.
-   Glider #2 adopted a simpler Depron construction with adjustable
    elevator geometry.
-   The reported drag-polar data show a reduction in
    **C`<sub>`{=html}L`</sub>`{=html}/C`<sub>`{=html}D`</sub>`{=html}
    from 5.12 to 3.08** across the measured lift-coefficient range.

## Report

The complete project documentation is available in `Report.pdf`.

The report is primarily a visual presentation containing prototype
photographs, experimental measurements, calculations, and the final
drag-polar plot.

## Notes

All numerical values and design descriptions in this README are based on
the accompanying project report. The README does not introduce
additional experimental results beyond those documented in the report.
