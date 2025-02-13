# Flexbox Percentage Width Issue
This repository demonstrates a common issue encountered when using percentages for width in CSS flexbox layouts.  Two elements within a flex container, each set to 50% width, do not always occupy the full width available, leading to unexpected spacing.

The bug is in the interaction of percentage widths within a flexbox environment. Flexbox can introduce inconsistencies when percentage-based widths don't add up to 100% due to rounding and the way flexbox handles space distribution.

The solution provides a more robust approach for achieving the desired layout.