# Samples

Copy a sample of interest into the .github/workflows folder.


## Examples of the expressions and contexts function in github actions.

In this context example, the `github.event_name` expression accesses the `event_nam`e property of the github context, which contains the name of the event that triggered the workflow. The echo command then prints a message that includes this event name.

There are several other contexts available in GitHub Actions, including `job`, `steps`, `runner`, `strategy`, `matrix`, and `secrets`. Each of these contexts provides access to a different set of data related to the workflow run.

    jobs:
    build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
        uses: actions/checkout@v2

        - name: Print event name
        run: echo "This workflow was triggered by a ${{ github.event_name }} event."

Example of the success function in github actions.

    jobs:
    build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
        uses: actions/checkout@v2

        - name: Run tests
        run: make test

        - name: Notify on success
        if: success()
        run: echo "Tests passed successfully!"


Example of the contains() function in github actions.

    jobs:
    build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
        uses: actions/checkout@v2

        - name: Run only if commit message contains 'test'
        run: echo "Running tests..."
        if: contains(github.event.head_commit.message, 'test')

Example of the contains() function in github actions.

    jobs:
    build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
        uses: actions/checkout@v2

        - name: Join strings
        run: echo "${{ join(['Hello', 'GitHub', 'Actions'], ' ') }}"