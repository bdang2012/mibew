# Mibew Tray Notification plugin

Plugin notifies a Mibew operator about new visitors requesting a chat in the Windows system tray.

<h2>Installation</h2>

Get the archive with the plugin sources. At the moment the only option is to build the plugin from sources.

    Untar/unzip the plugin's archive.

Put files of the plugins to the <Mibew root>/plugins folder.
(optional) Add plugins configs to "plugins" structure in "<Mibew root>/configs/config.yml". If the "plugins" stucture looks like plugins: [] it will become:

    plugins:
        "AARInnovations:TrayNotification": # Plugin's configurations are described below
            new_thread: true

Navigate to "<Mibew Base URL>/operator/plugin" page and enable the plugin.

Downdload plugin package ready to install and find more details at <a href="http://aar-innovations.com">http://aar-innovations.com</a>

<h2>Build from sources</h2>

There are several actions one should do before use the latest version of the plugin from the repository:
<ol>
<li>Obtain a copy of the repository using git clone, download button, or another way.</li>
<li>Install <a href="http://nodejs.org/">node.js</a> and <a href="https://www.npmjs.org/">npm</a>.</li>
<li>Install <a href="http://gulpjs.com/">Gulp</a>.</li>
<li>Install npm dependencies using npm install.</li>
<li>Run Gulp to build the sources using gulp default.</li>
</ol>
Finally .tar.gz and .zip archives of the ready-to-use Plugin will be available in release directory.

<h2>License</h2>
<a href="http://www.apache.org/licenses/LICENSE-2.0.html">Apache License 2.0</a>
