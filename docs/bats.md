<!-- Generated with Stardoc: http://skydoc.bazel.build -->

Bats test runner

<a id="bats_test"></a>

## bats_test

<pre>
bats_test(<a href="#bats_test-name">name</a>, <a href="#bats_test-data">data</a>, <a href="#bats_test-env">env</a>, <a href="#bats_test-srcs">srcs</a>)
</pre>



**ATTRIBUTES**


| Name  | Description | Type | Mandatory | Default |
| :------------- | :------------- | :------------- | :------------- | :------------- |
| <a id="bats_test-name"></a>name |  A unique name for this target.   | <a href="https://bazel.build/concepts/labels#target-names">Name</a> | required |  |
| <a id="bats_test-data"></a>data |  Runtime dependencies of the test.   | <a href="https://bazel.build/concepts/labels">List of labels</a> | optional | <code>[]</code> |
| <a id="bats_test-env"></a>env |  Environment variables of the action.<br><br>            Subject to [$(location)](https://bazel.build/reference/be/make-variables#predefined_label_variables)             and ["Make variable"](https://bazel.build/reference/be/make-variables) substitution.   | <a href="https://bazel.build/rules/lib/dict">Dictionary: String -> String</a> | optional | <code>{}</code> |
| <a id="bats_test-srcs"></a>srcs |  Test files   | <a href="https://bazel.build/concepts/labels">List of labels</a> | optional | <code>[]</code> |


