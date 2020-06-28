# EPL Containers
Apama EPL Classes for container types - Heap, Stack, Queue, CircularBuffer

## Supported Apama version

This works with Apama 10.5 or later, and probably most of the earlier ones as well

## Using containers numbers from EPL

To use the containers from EPL, add the relevant .mon file (eg Stack.mon) to your project, or ensure you inject it before your EPL code. Then import the relevant event into your file with:

	using com.apamax.containers.Stack;

## Running tests

To run the tests you will need to use an Apama command prompt to run the tests from within the tests directory:

    pysys run

## API documentation

API documentation can be found here: [API documentation](https://mjj29.github.io/apama-epl-containers/)
