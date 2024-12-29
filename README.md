This repository demonstrates a subtle bug in R's subsetting mechanism using logical vectors. When a logical vector is longer than the number of rows in a data frame, R silently truncates the extra elements without warning. This can lead to unexpected behavior and difficult-to-debug errors. The `bug.R` file contains the problematic code, while `bugSolution.R` shows how to mitigate this issue by checking the length of the logical vector before subsetting.