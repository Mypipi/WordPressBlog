=== Gutenberg ===
Contributors: matveb, joen, karmatosed
Requires at least: 5.1.0
Tested up to: 5.2
Stable tag: 5.9.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The block editor was introduced in core WordPress with version 5.0. This beta plugin allows you to test bleeding-edge features around editing and customization projects before they land in future WordPress releases.

== Description ==

Gutenberg is more than an editor. While the editor is the focus right now, the project will ultimately impact the entire publishing experience including customization (the next focus area).

<a href="https://wordpress.org/gutenberg">Discover more about the project</a>.

= Editing focus =

> The editor will create a new page- and post-building experience that makes writing rich posts effortless, and has “blocks” to make it easy what today might take shortcodes, custom HTML, or “mystery meat” embed discovery. — Matt Mullenweg

One thing that sets WordPress apart from other systems is that it allows you to create as rich a post layout as you can imagine -- but only if you know HTML and CSS and build your own custom theme. By thinking of the editor as a tool to let you write rich posts and create beautiful layouts, we can transform WordPress into something users _love_ WordPress, as opposed something they pick it because it's what everyone else uses.

Gutenberg looks at the editor as more than a content field, revisiting a layout that has been largely unchanged for almost a decade.This allows us to holistically design a modern editing experience and build a foundation for things to come.

Here's why we're looking at the whole editing screen, as opposed to just the content field:

1. The block unifies multiple interfaces. If we add that on top of the existing interface, it would _add_ complexity, as opposed to remove it.
2. By revisiting the interface, we can modernize the writing, editing, and publishing experience, with usability and simplicity in mind, benefitting both new and casual users.
3. When singular block interface takes center stage, it demonstrates a clear path forward for developers to create premium blocks, superior to both shortcodes and widgets.
4. Considering the whole interface lays a solid foundation for the next focus, full site customization.
5. Looking at the full editor screen also gives us the opportunity to drastically modernize the foundation, and take steps towards a more fluid and JavaScript powered future that fully leverages the WordPress REST API.

= Blocks =

Blocks are the unifying evolution of what is now covered, in different ways, by shortcodes, embeds, widgets, post formats, custom post types, theme options, meta-boxes, and other formatting elements. They embrace the breadth of functionality WordPress is capable of, with the clarity of a consistent user experience.

Imagine a custom “employee” block that a client can drag to an About page to automatically display a picture, name, and bio. A whole universe of plugins that all extend WordPress in the same way. Simplified menus and widgets. Users who can instantly understand and use WordPress  -- and 90% of plugins. This will allow you to easily compose beautiful posts like <a href="http://moc.co/sandbox/example-post/">this example</a>.

Check out the <a href="https://wordpress.org/gutenberg/handbook/reference/faq/">FAQ</a> for answers to the most common questions about the project.

= Compatibility =

Posts are backwards compatible, and shortcodes will still work. We are continuously exploring how highly-tailored metaboxes can be accommodated, and are looking at solutions ranging from a plugin to disable Gutenberg to automatically detecting whether to load Gutenberg or not. While we want to make sure the new editing experience from writing to publishing is user-friendly, we’re committed to finding  a good solution for highly-tailored existing sites.

= The stages of Gutenberg =

Gutenberg has three planned stages. The first, aimed for inclusion in WordPress 5.0, focuses on the post editing experience and the implementation of blocks. This initial phase focuses on a content-first approach. The use of blocks, as detailed above, allows you to focus on how your content will look without the distraction of other configuration options. This ultimately will help all users present their content in a way that is engaging, direct, and visual.

These foundational elements will pave the way for stages two and three, planned for the next year, to go beyond the post into page templates and ultimately, full site customization.

Gutenberg is a big change, and there will be ways to ensure that existing functionality (like shortcodes and meta-boxes) continue to work while allowing developers the time and paths to transition effectively. Ultimately, it will open new opportunities for plugin and theme developers to better serve users through a more engaging and visual experience that takes advantage of a toolset supported by core.

= Contributors =

Gutenberg is built by many contributors and volunteers. Please see the full list in <a href="https://github.com/WordPress/gutenberg/blob/master/CONTRIBUTORS.md">CONTRIBUTORS.md</a>.

== Frequently Asked Questions ==

= How can I send feedback or get help with a bug? =

We'd love to hear your bug reports, feature suggestions and any other feedback! Please head over to <a href="https://github.com/WordPress/gutenberg/issues">the GitHub issues page</a> to search for existing issues or open a new one. While we'll try to triage issues reported here on the plugin forum, you'll get a faster response (and reduce duplication of effort) by keeping everything centralized in the GitHub repository.

= How can I contribute? =

We’re calling this editor project "Gutenberg" because it's a big undertaking. We are working on it every day in GitHub, and we'd love your help building it.You’re also welcome to give feedback, the easiest is to join us in <a href="https://make.wordpress.org/chat/">our Slack channel</a>, `#core-editor`.

See also <a href="https://github.com/WordPress/gutenberg/blob/master/CONTRIBUTING.md">CONTRIBUTING.md</a>.

= Where can I read more about Gutenberg? =

- <a href="http://matiasventura.com/post/gutenberg-or-the-ship-of-theseus/">Gutenberg, or the Ship of Theseus</a>, with examples of what Gutenberg might do in the future
- <a href="https://make.wordpress.org/core/2017/01/17/editor-technical-overview/">Editor Technical Overview</a>
- <a href="https://wordpress.org/gutenberg/handbook/reference/design-principles/">Design Principles and block design best practices</a>
- <a href="https://github.com/Automattic/wp-post-grammar">WP Post Grammar Parser</a>
- <a href="https://make.wordpress.org/core/tag/gutenberg/">Development updates on make.wordpress.org</a>
- <a href="https://wordpress.org/gutenberg/handbook/">Documentation: Creating Blocks, Reference, and Guidelines</a>
- <a href="https://wordpress.org/gutenberg/handbook/reference/faq/">Additional frequently asked questions</a>


== Changelog ==

### Features

* Support choosing a [pre-defined layout for the Columns block](https://github.com/WordPress/gutenberg/pull/16129). 

### Enhancements

* Add [Snackbar notices](https://github.com/WordPress/gutenberg/pull/16020) support to the widgets screen.
* Add an [inner container to the Group](https://github.com/WordPress/gutenberg/pull/15210) [block](https://github.com/WordPress/gutenberg/pull/16202) to simplify theme styling.
* Avoid stacking successive [MediaPlaceholder errors](https://github.com/WordPress/gutenberg/pull/14721).
* Adjust the [DatePicker margins](https://github.com/WordPress/gutenberg/pull/16097).
* Update the [Tag Cloud block](https://github.com/WordPress/gutenberg/pull/16098) [copy](https://github.com/WordPress/gutenberg/pull/16107) when no terms are found.
* Add descriptive text and a link to [documentation in embed blocks](https://github.com/WordPress/gutenberg/pull/16101).
* Improve placeholder text [phrasing for media blocks](https://github.com/WordPress/gutenberg/pull/16135).
* Use classnames for the [text alignments in the heading block](https://github.com/WordPress/gutenberg/pull/16035).
* Make the [inserter category icons grayscale](https://github.com/WordPress/gutenberg/pull/16163).
* A11y: Make the [modal overlay scrim darker](https://github.com/WordPress/gutenberg/pull/15974).

### Bug Fixes

* Fix [warning messages triggered by the Group block](https://github.com/WordPress/gutenberg/pull/16096) icons.
* Fix [horizontal scrollbar on full-wide blocks](https://github.com/WordPress/gutenberg/pull/16085) with nesting.
* A11y: 
  * Re-enable the [menu item hover state](https://github.com/WordPress/gutenberg/pull/16168) on small screens.
  * Correct text zoom issue in the [Content Structure popover](https://github.com/WordPress/gutenberg/pull/15984).
* Fix the [Popovers position](https://github.com/WordPress/gutenberg/pull/15949) in the widgets screen.
* Fix the behavior of the [block toolbars in the widgets screen](https://github.com/WordPress/gutenberg/pull/15470).
* Fix the editor in IE11 (use the [CJS version of react-spring](https://github.com/WordPress/gutenberg/pull/16196)).
* Fix formatting of the [validation error messages](https://github.com/WordPress/gutenberg/pull/16173) in the console.
* Fix breakage when the [CPT doesn’t support title](https://github.com/WordPress/gutenberg/pull/16236).

### Various

* Document and simplify the [multi-entrypoints support](https://github.com/WordPress/gutenberg/pull/15982) in the @wordpress/scripts package. 
* Create sub-registry automatically when using [EditorProvider](https://github.com/WordPress/gutenberg/pull/15989).
* Use classnames utility instead of concatenating [classnames in the TabPanel](https://github.com/WordPress/gutenberg/pull/16081) component.
* Remove the default value for the [required onRequestClose prop](https://github.com/WordPress/gutenberg/pull/16074) in the Modal component.
* Remove the [editor package dependency](https://github.com/WordPress/gutenberg/pull/15548) from the media blocks.
* Fix the [playground build](https://github.com/WordPress/gutenberg/pull/15947) script.
* Fix the [Github action assigning milestones](https://github.com/WordPress/gutenberg/pull/16084).
* Fix [naming conventions](https://github.com/WordPress/gutenberg/pull/16091) for function containing CLI keyword.
* Fix the [Travis build artifacts job](http://update/build-artifacts-npm-install) to use a full npm install while building.
* Make [Calendar block resilient](https://github.com/WordPress/gutenberg/pull/16161) to the editor module not being present.
* Ensure the Snackbar component is only used with a [single action button](https://github.com/WordPress/gutenberg/pull/16095).
* Remove [SlotFillProvider and DropZoneProvider](https://github.com/WordPress/gutenberg/pull/15988) from the BlockEditorProvider.
* Add the initial version of the [Block Registration RFC](https://github.com/WordPress/gutenberg/pull/13693).
* Add [popoverProps prop to the Dropdown](https://github.com/WordPress/gutenberg/pull/14867) component.
* Update [Image Block's image classes](https://github.com/WordPress/gutenberg/pull/15464) with dimensions.
* Support registering [custom grouping blocks](https://github.com/WordPress/gutenberg/pull/15774).
* Fix h1 heading typo so [h1 is same size as title](https://github.com/WordPress/gutenberg/pull/16253).
* Remove the [custom class support from the legacy widget](https://github.com/WordPress/gutenberg/pull/16231) block.

### Documentation

* Prefer [register\_post\_meta](https://github.com/WordPress/gutenberg/pull/16032) over register\_meta.
* Add [mention of Figma](https://github.com/WordPress/gutenberg/pull/16140) to the design contributing docs.
* Add [supported attribute types](https://github.com/WordPress/gutenberg/pull/16220) for the Blocks API.
* Enhance the [Annotations API](https://github.com/WordPress/gutenberg/pull/16233) documentation.
* Tweaks and typos: [1](https://github.com/WordPress/gutenberg/pull/16083), [2](https://github.com/WordPress/gutenberg/pull/16073), [3](https://github.com/WordPress/gutenberg/pull/16087), [4](https://github.com/WordPress/gutenberg/pull/16102), [5](https://github.com/WordPress/gutenberg/pull/16145), [6](https://github.com/WordPress/gutenberg/pull/16143), [7](https://github.com/WordPress/gutenberg/pull/16144), [8](https://github.com/WordPress/gutenberg/pull/16232), [9](https://github.com/WordPress/gutenberg/pull/16121), [10](https://github.com/WordPress/gutenberg/pull/16235), [11](https://github.com/WordPress/gutenberg/pull/15394).

### Mobile

* Fix [multiline Image block captions](https://github.com/WordPress/gutenberg/pull/16071) in iOS.
* Avoid unnecessary [div elements in the content of Quote](https://github.com/WordPress/gutenberg/pull/16072) blocks.
* Update the default [colors used in the RichText](https://github.com/WordPress/gutenberg/pull/16016) component.
* Fix [pasting text on Post Title](https://github.com/WordPress/gutenberg/pull/16116).
* Unify the web and mobile components hierarchy:
  * [BlockPicker and Inserter](https://github.com/WordPress/gutenberg/pull/16114).
  * [BlockToolbar](https://github.com/WordPress/gutenberg/pull/16213).
  * [BlockMobileToolbar](https://github.com/WordPress/gutenberg/pull/16177).
  * [BlockListBlock](https://github.com/WordPress/gutenberg/pull/16223).
  * [BlockList](https://github.com/WordPress/gutenberg/pull/16239).
* Add native component [HTMLTextInput](https://github.com/WordPress/gutenberg/pull/16226).
* Update the video player to [open the URL by browser](https://github.com/WordPress/gutenberg/pull/16089) on Android.
* Re-enable the [Video block on Android](https://github.com/WordPress/gutenberg/pull/16215).

