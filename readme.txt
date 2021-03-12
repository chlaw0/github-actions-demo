name: Greeting from Law Chun Ho
on: push
jobs:
my-job:
name: My Job
runs-on: ubuntu-latest
steps:
- name: Print a greeting
env:
MY_VAR: Hi there! My name is
FIRST_NAME: Ho
MIDDLE_NAME: Chun
LAST_NAME: Law
run: |
echo $MY_VAR $FIRST_NAME $MIDDLE_NAME $LAST_NAME.
