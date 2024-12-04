# PHP Implicit Return Bug

This repository demonstrates a common, yet subtle, error in PHP: omitting an explicit `return` statement in a function. While PHP allows implicit returns (often returning `null`), this can lead to unexpected behavior and difficult-to-debug issues. The `bug.php` file contains the erroneous code, and `bugSolution.php` provides the corrected version.

**Bug:** The `myFunc()` function lacks an explicit `return` statement, resulting in an implicit return of `null`.

**Solution:** Adding an explicit `return` statement ensures predictable and controlled function behavior.