# `expo export` platform issue
To simulate error run `yarn export`

## Expected behavior
Export command will look in `app.json` on plaforms and builds only supported platforms

## Current behavior
Export command builds `ios` and `android`. No matter what.

