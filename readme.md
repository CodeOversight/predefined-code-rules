# A collection of example code rules

In here you can find a collection of popular code rules used by developers. 

## Usage

First look if there's a folder available with the preferred configuration for your project. When you found the code rule set you wnt to you, go in the folder and copy the `codeoversight.yml` file over to the root of your repository. 

## Contributing

We love to see you contribute to the predefined configurations. Feel free to add new configuration sets that are commonly used or propose a change when you think something should change. Please do include references on why it should change.

**Would like to contribute and walk things over in real time with us? [Just shoot us a message!](http://codeoversight.com/contact)**

## Template file

The code below is a useful template file where all the code rules with their allowed values are listed.


```yaml
# Lang  code_rule_name                                set_value   Possible values
php:
    align_array_elements:                             no_apply    # space, tab
    align_doc_tags:                                   no_apply    # space, double_space, triple_space, quadruple_space, tab
    align_variables:                                  no_apply    # space, tab
    closing_newline:                                  no_apply    # add, remove
    closing_php_tag:                                  no_apply    # remove, add
    control_structure_parentheses_inner_whitespace:   no_apply    # no_space, whitespace
    doc_function_whitespace:                          no_apply    # no_space, newline
    else_if_whitespace:                               no_apply    # no_space, whitespace
    exclamation_whitespace:                           no_apply    # whitespace, no_space
    force_control_structure_braces:                   no_apply    # force
    function_args_separator_whitespace:               no_apply    # whitespace, no_space
    function_parentheses_inner_whitespace:            no_apply    # whitespace, no_space
    indentation_whitespace:                           no_apply    # tab, space
    opening_doc_asterisk:                             no_apply    # double
    php_tag_casing:                                   no_apply    # lower, upper
    php_tags:                                         no_apply    # full_php_tags, short_php_tags
    remove_double_semicolon:                          no_apply    # remove
    remove_empty_trailing_leading_doc_lines:          no_apply    # remove
    semicolon_before_closing_php_tag:                 no_apply    # add, remove
    static_array_index_whitespace:                    no_apply    # no_space, whitespace
    string_operator_whitespace:                       no_apply    # whitespace, no_space
    trailing_whitespace:                              no_apply    # remove
    true_false_casing:                                no_apply    # lower, upper
    type_cast_casing:                                 no_apply    # lower, upper
    type_cast_inner_whitespace:                       no_apply    # whitespace, no_space
    use_quotes:                                       no_apply    # single_quotes, double_quotes
    variable_array_index_whitespace:                  no_apply    # whitespace, no_space
    whitespace_after_control_structure:               no_apply    # no_space, whitespace
    whitespace_after_doc_asterisk:                    no_apply    # single_space, double_space, tab
    whitespace_after_else:                            no_apply    # space, newline, no_space
    whitespace_after_function_open:                   no_apply    # newline, no_space
    whitespace_after_function:                        no_apply    # newline, double_newline
    whitespace_before_control_structure_brace:        no_apply    # space, newline, no_space
    whitespace_before_doc_asterisk:                   no_apply    # space
    whitespace_before_else:                           no_apply    # space, newline, no_space
    whitespace_before_function_brace:                 no_apply    # space, newline, no_space
    whitespace_before_function_close:                 no_apply    # newline, no_space
    whitespace_before_function_parentheses:           no_apply    # no_space, whitespace
```
