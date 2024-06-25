# Tailwind CSS with Daisy UI for Rails

This combines the tailwindcss-rails gem with an alternate binary that includes DaisyUI.  

* tailwindcss-rails gem courtesy of https://github.com/rails/tailwindcss-rails
* DaisyUI+tailwind binary courtesy of https://github.com/dobicinaitis/tailwind-cli-extra

With this the goal is to allow DaisyUI & tailwind to work in Rails the same way tailwindcss-rails works.  That is:
* with import-maps
* without a node installation
* without a JS bundler
* with unused tailwindcss & daisy styles stripped

# WIP

This is WIP but works experimentally.  Likely will convert this into its own gem. It may work as a fork but is likely less maintainable.
I'm considering a re-write to make this more of a build-script combining the two.

