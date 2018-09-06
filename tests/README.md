Tests and Coverage
================
06 September, 2018 02:23:19

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

| Object                                             | Coverage (%) |
| :------------------------------------------------- | :----------: |
| covrpage                                           |    15.34     |
| [R/badge.R](../R/badge.R)                          |     0.00     |
| [R/coverage\_skip.R](../R/coverage_skip.R)         |     0.00     |
| [R/covrpage\_snapshot.R](../R/covrpage_snapshot.R) |     0.00     |
| [R/covrpage.R](../R/covrpage.R)                    |     0.00     |
| [R/map\_testthat.R](../R/map_testthat.R)           |     0.00     |
| [R/tencrypt.R](../R/tencrypt.R)                    |     0.00     |
| [R/use\_covrpage.R](../R/use_covrpage.R)           |     0.00     |
| [R/vignette.R](../R/vignette.R)                    |     0.00     |
| [R/covrpage\_checks.R](../R/covrpage_checks.R)     |    21.43     |
| [R/testthat\_summary.R](../R/testthat_summary.R)   |    69.35     |
| [R/create\_chunks.R](../R/create_chunks.R)         |    96.00     |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat)
package.

|                     | file                                               | n |  time | error | failed | skipped | warning |
| ------------------- | :------------------------------------------------- | -: | ----: | ----: | -----: | ------: | ------: |
| test-check\_utils.R | [test-check\_utils.R](testthat/test-check_utils.R) | 6 | 0.084 |     0 |      0 |       1 |       1 |
| test-covrfuns.R     | [test-covrfuns.R](testthat/test-covrfuns.R)        | 6 | 0.105 |     0 |      0 |       0 |       0 |

<details open>

<summary> Show Detailed Test Results
</summary>

| file                                                   | context                    | test                           | status  | n |  time |
| :----------------------------------------------------- | :------------------------- | :----------------------------- | :------ | -: | ----: |
| [test-check\_utils.R](testthat/test-check_utils.R#L4)  | check for tests            | tests are detected             | PASS    | 1 | 0.022 |
| [test-check\_utils.R](testthat/test-check_utils.R#L12) | check for packages         | packages are detected          | SKIPPED | 3 | 0.026 |
| [test-check\_utils.R](testthat/test-check_utils.R#L22) | use covrpage               | test use\_covrpage             | WARNING | 2 | 0.036 |
| [test-covrfuns.R](testthat/test-covrfuns.R#L5)         | check summary covr         | covr\_summary: standard input  | PASS    | 1 | 0.049 |
| [test-covrfuns.R](testthat/test-covrfuns.R#L9_L11)     | check summary covr         | covr\_summary: empty input     | PASS    | 1 | 0.003 |
| [test-covrfuns.R](testthat/test-covrfuns.R#L19)        | check summary output types | with data: short               | PASS    | 1 | 0.034 |
| [test-covrfuns.R](testthat/test-covrfuns.R#L23)        | check summary output types | with data: long                | PASS    | 1 | 0.017 |
| [test-covrfuns.R](testthat/test-covrfuns.R#L27)        | check summary output types | with data: no data             | PASS    | 1 | 0.001 |
| [test-covrfuns.R](testthat/test-covrfuns.R#L35)        | check covr to df           | covr object to df: empty input | PASS    | 1 | 0.001 |

</details>

<details>

<summary> Session Info </summary>

| Field    | Value                         |
| :------- | :---------------------------- |
| Version  | R version 3.5.0 (2017-01-27)  |
| Platform | x86\_64-pc-linux-gnu (64-bit) |
| Running  | Ubuntu 14.04.5 LTS            |
| Language | en\_US                        |
| Timezone | UTC                           |

| Package  | Version |
| :------- | :------ |
| testthat | 2.0.0   |
| covr     | 3.1.0   |
| covrpage | 0.0.55  |

</details>

<!--- Final Status : skipped/warning --->
