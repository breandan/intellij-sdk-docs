* [IntelliJ Platform SDK](index.md)
  * [Quick Start Guide](basics.md)
    * [Main Types of IntelliJ IDEA Plugins](basics/types_of_plugins.md)
    * [Creating Your First Plugin](basics/getting_started.md)
      * [Setting Up Development Environment](basics/getting_started/setting_up_environment.md)
      * [Creating a Plugin Project](basics/getting_started/creating_plugin_project.md)
      * [Build Number Ranges](basics/getting_started/build_number_ranges.md)
      * [Running and Debugging a Plugin](basics/getting_started/running_and_debugging_a_plugin.md)
      * [Deploying a Plugin](basics/getting_started/deploying_plugin.md)
      * [Plugin Compatibility with IntelliJ Platform Products](basics/getting_started/plugin_compatibility.md)
      * [Plugin Structure](basics/plugin_structure.md)
        * [Plugin Content](basics/plugin_structure/plugin_content.md)
        * [Plugin Class Loaders](basics/plugin_structure/plugin_class_loaders.md)
        * [Plugin Components](basics/plugin_structure/plugin_components.md)
        * [Plugin Extensions and Extension Points](basics/plugin_structure/plugin_extensions_and_extension_points.md)
        * [Plugin Actions](basics/plugin_structure/plugin_actions.md)
        * [Plugin Services](basics/plugin_structure/plugin_services.md)
        * [Plugin Configuration File](basics/plugin_structure/plugin_configuration_file.md)
        * [Plugin Dependencies](basics/plugin_structure/plugin_dependencies.md)
    * [Architectural Overview](basics/architectural_overview.md)
      * [General Threading Rules](basics/architectural_overview/general_threading_rules.md)
      * [Virtual Files](basics/architectural_overview/virtual_file.md)
      * [Documents](basics/architectural_overview/documents.md)
      * [PSI Files](basics/architectural_overview/psi_files.md)
      * [File View Providers](basics/architectural_overview/file_view_providers.md)
      * [PSI Elements](basics/architectural_overview/psi_elements.md)
    * [Project Structure](basics/project_structure.md)
      * [Action System](basics/action_system.md)
      * [Persisting State of Components](basics/persisting_state_of_components.md)
      * [PSI Cookbook](basics/psi_cookbook.md)
      * [Virtual File System](basics/virtual_file_system.md)
    * [Check Out And Build Community Edition](basics/checkout_and_build_community.md)
    * [IDE Settings, Caches, Logs, and Plugins](basics/settings_caches_logs.md)
    * [Indexing and PSI Stubs](basics/indexing_and_psi_stubs.md)
      * [File-based indexes](basics/indexing_and_psi_stubs/file_based_indexes.md)
      * [Stub indexes](basics/indexing_and_psi_stubs/stub_indexes.md)
    * [Run Configurations](basics/run_configurations.md)
      * [Run Configuration Management](basics/run_configurations/run_configuration_management.md)
      * [Execution](basics/run_configurations/run_configuration_execution.md)
    * [Testing Plugins](basics/testing_plugins.md)
      * [Tests and Fixtures](basics/testing_plugins/tests_and_fixtures.md)
      * [Light and Heavy Tests](basics/testing_plugins/light_and_heavy_tests.md)
      * [Test Project and Testdata Directories](basics/testing_plugins/test_project_and_testdata_directories.md)
      * [Writing Tests](basics/testing_plugins/writing_tests.md)
      * [Testing Highlighting](basics/testing_plugins/testing_highlighting.md)
  * [Architecture Reference Guide](reference_guide.md)
    * [Project Model](reference_guide/project_model.md)
      * [Project](reference_guide/project_model/project.md)
      * [Module](reference_guide/project_model/module.md)
      * [SDK](reference_guide/project_model/sdk.md)
      * [Library](reference_guide/project_model/library.md)
      * [Facet](reference_guide/project_model/facet.md)
    * [Project Wizard](reference_guide/project_wizard.md)
    * [Custom Language Support](reference_guide/custom_language_support.md)
      * [Registering File Type](reference_guide/custom_language_support/registering_file_type.md)
      * [Implementing Lexer](reference_guide/custom_language_support/implementing_lexer.md)
      * [Implementing Parser and PSI](reference_guide/custom_language_support/implementing_parser_and_psi.md)
      * [Syntax Highlighting and Error Highlighting](reference_guide/custom_language_support/syntax_highlighting_and_error_highlighting.md)
      * [References and Resolve](reference_guide/custom_language_support/references_and_resolve.md)
      * [Code Completion](reference_guide/custom_language_support/code_completion.md)
      * [Find Usages](reference_guide/custom_language_support/find_usages.md)
      * [Rename Refactoring](reference_guide/custom_language_support/rename_refactoring.md)
      * [Safe Delete Refactoring](reference_guide/custom_language_support/safe_delete_refactoring.md)
      * [Code Formatter](reference_guide/custom_language_support/code_formatting.md)
      * [Code Inspections and Intentions](reference_guide/custom_language_support/code_inspections_and_intentions.md)
      * [Structure View](reference_guide/custom_language_support/structure_view.md)
      * [Surround With](reference_guide/custom_language_support/surround_with.md)
      * [Go to Class and Go to Symbol](reference_guide/custom_language_support/go_to_class_and_go_to_symbol.md)
      * [Documentation](reference_guide/custom_language_support/documentation.md)
      * [Additional Minor Features](reference_guide/custom_language_support/additional_minor_features.md)
    * [Frameworks and External APIs](reference_guide/frameworks_and_external_apis.md)
      * [XML DOM API](reference_guide/frameworks_and_external_apis/xml_dom_api.md)
      * [Spring API](reference_guide/frameworks_and_external_apis/spring_api.md)
      * [External Builder API and Plugins](reference_guide/frameworks_and_external_apis/external_builder_api.md)
    * [VCS Integration Plugins](reference_guide/vcs_integration_for_plugins.md)
    * [Localization Guide](reference_guide/localization_guide.md)
    * [Messaging Infrastructure](reference_guide/messaging_infrastructure.md)
    * [Multiple Carets](reference_guide/multiple_carets.md)
    * [Color Scheme Management](reference_guide/color_scheme_management.md)
      * [Work with Icons and Images](reference_guide/work_with_icons_and_images.md)
      * [Tomcat Integration](reference_guide/tomcat_integration.md)
    * [User Interface Components](user_interface_components/user_interface_components.md)
      * [Tool Windows](user_interface_components/tool_windows.md)
      * [Dialogs](user_interface_components/dialog_wrapper.md)
      * [Popups](user_interface_components/popups.md)
      * [Notifications](user_interface_components/notifications.md)
      * [File and Class Choosers](user_interface_components/file_and_class_choosers.md)
      * [Editor Components](user_interface_components/editor_components.md)
      * [List and Tree Controls](user_interface_components/lists_and_trees.md)
      * [Miscellaneous Swing Components](user_interface_components/misc_swing_components.md)
  * PHPStorm and WebStorm
  * [Tutorials](tutorials.md)
    * [Custom Language Support](tutorials/custom_language_support_tutorial.md)
      * [1. Prerequisites](tutorials/custom_language_support/prerequisites.md)
      * [2. Language and File Type](tutorials/custom_language_support/language_and_filetype.md)
      * [3. Grammar and Parser](tutorials/custom_language_support/grammar_and_parser.md)
      * [4. Lexer and Parser Definition](tutorials/custom_language_support/lexer_and_parser_definition.md)
      * [5. Syntax Highlighter and Color Settings Page](tutorials/custom_language_support/syntax_highlighter_and_color_settings_page.md)
      * [6. PSI Helpers and Utilities](tutorials/custom_language_support/psi_helper_and_utilities.md)
      * [7. Annotator](tutorials/custom_language_support/annotator.md)
      * [8. Line Marker Provider](tutorials/custom_language_support/line_marker_provider.md)
      * [9. Completion Contributor](tutorials/custom_language_support/completion_contributor.md)
      * [10. Reference Contributor](tutorials/custom_language_support/reference_contributor.md)
      * [11. Find Usages Provider](tutorials/custom_language_support/find_usages_provider.md)
      * [12. Folding Builder](tutorials/custom_language_support/folding_builder.md)
      * [13. Go To Symbol Contributor](tutorials/custom_language_support/go_to_symbol_contributor.md)
      * [14. Structure View Factory](tutorials/custom_language_support/structure_view_factory.md)
      * [15. Formatter](tutorials/custom_language_support/formatter.md)
      * [16. Code Style Settings](tutorials/custom_language_support/code_style_settings.md)
      * [17. Commenter](tutorials/custom_language_support/commenter.md)
      * [18. Quick Fix](tutorials/custom_language_support/quick_fix.md)
    * [Writing Tests For Plugins](tutorials/writing_tests_for_plugins.md)
      * [1. Tests Prerequisites](tutorials/writing_tests_for_plugins/tests_prerequisites.md)
      * [2. Parsing Test](tutorials/writing_tests_for_plugins/parsing_test.md)
      * [3. Completion Test](tutorials/writing_tests_for_plugins/completion_test.md)
      * [4. Annotator Test](tutorials/writing_tests_for_plugins/annotator_test.md)
      * [5. Formatter Test](tutorials/writing_tests_for_plugins/formatter_test.md)
      * [6. Rename Test](tutorials/writing_tests_for_plugins/rename_test.md)
      * [7. Folding Test](tutorials/writing_tests_for_plugins/folding_test.md)
      * [8. Find Usages Test](tutorials/writing_tests_for_plugins/find_usages_test.md)
      * [9. Commenter Test](tutorials/writing_tests_for_plugins/commenter_test.md)
      * [10. Reference Test](tutorials/writing_tests_for_plugins/reference_test.md)
    * [Action System](tutorials/action_system.md)
      * [1. Working With Custom Actions](tutorials/action_system/working_with_custom_actions.md)
      * [2. Grouping Actions](tutorials/action_system/grouping_action.md)
    * [Editor Basics](tutorials/editor_basics.md)
      * [1. Working With Text](tutorials/editor_basics/working_with_text.md)
      * [2. Editor Coordinates System. Positions And Offsets](tutorials/editor_basics/coordinates_system.md)
      * [3. Handling Editor Events](tutorials/editor_basics/editor_events.md)
    * [Project Wizard](tutorials/project_wizard.md)
      * [Adding New Steps to Project Wizard](tutorials/project_wizard/adding_new_steps.md)
      * [Supporting Module Types](tutorials/project_wizard/module_types.md)
  <!-- * [Code Inspections](tutorials/code_inspections.md) -->
    * [Run Configurations](tutorials/run_configurations.md)
    * [Supporting Frameworks](tutorials/framework.md)
    * [Tree Structure View](tutorials/tree_structure_view.md)
  * [Plugin Development FAQ](faq.md)
  * [Contribution Guidelines](CONTRIBUTING.md)



