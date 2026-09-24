Test 1 IS218
Fangze Wang
Making a pytest and learning how to:
-push files to github
-use branches
-create and close issues
-view actions to verify correctness

CREATE VIRTUAL ENVIRONMENT WITH PYTHON 3.13.15:
python3 -m venv .venv
ACTIVATE VIRTUAL ENVIRONMENT:
source .venv/bin/activate
INSTALL REQUIRED DEPENDENCIES:
python -m pip install -r requirements.txt

RUNNING THE TESTS:
python -m pytest
RUNNING TESTS WITH SUPPLIED ACCEPTANCE CASES:
python -m pytest tests checks -v

GITHUB LINKS:
https://github.com/FangzeW1/is218_test1_official/issues/1
https://github.com/FangzeW1/is218_test1_official/issues/2
https://github.com/FangzeW1/is218_test1_official/issues/3
https://github.com/FangzeW1/is218_test1_official/issues/4

TEST EXAMPLE:
The test_add_zero() test uses the inputs 7 and 0 and expects a result of 7. The assertion is that adding a number with 0 returns to the original number.

The requirements.txt file is committed so that the project's dependencies can be installed consistently. The .venv directory is ignored because it contains local, environment-specific files that can be recreated from requirements.txt.