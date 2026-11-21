# Why deeper filters last

https://mattnewell-cam.github.io/why-deeper-filters-last/

An animated explainer of why an electret filter with more material, split between more layers and more
area, stays above its protection target far longer than its material alone suggests. Two filters run side
by side on the same dusty air; a slider sets how much more material the second one gets.

Two effects:
- It starts further above the target, so it has more charge to lose.
- Spent (discharged) front layers keep catching dust mechanically, so less and less reaches the charged
  layers behind them.

Simplified model (all on the page under Assumptions): per-layer PF 20 charged and 2.4 discharged; logs fall
in a straight line from charged to discharged as a layer's charge goes, in proportion to the dust it has
caught per m²; dust rate set so a single layer loses 41% of its logs in 6.45 days, as in an ambient-air test;
more area lowers face speed, and per-layer logs go as face speed^−0.307; target PF 1,000 the whole time;
pressure drop goes as layers ÷ area; clogging left out.

Single file, no build step.
