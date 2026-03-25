# PHTS NP-01: IR controller configs

Remote control configurations for [IR Controller] Volumio plugin used by [PHTS NP-01].

## Current mappings

<table>
  <thead><tr>
  <th></th>
  <th>Button</th>
  <th>Action</th>
  </tr></thead>
  <tbody>
    <tr>
      <th colspan=3>Yamaha RAS13</th>
    </tr>
    <tr>
      <td rowspan=12>
        <img height=500 src="https://community.volumio.com/uploads/default/original/3X/c/4/c43a32c5bdfd5d9c62aaf5f9d8ba595b9bd1a94e.jpeg">
      </td>
      <td><code>BAND</code></td><td>Toggle screen modes: "Track info", "VU meter", "Screensaver"</td>
    </tr>
    <tr><td><code><< TUNING >></code></td><td>Toggle background image for "Screensaver" screen mode</td></tr>
    <tr><td><code>MEMORY</code></td><td>Play selected playlist</td></tr>
    <tr><td><code>< PRESET > </code></td><td>Select previous/next playlist</td></tr>
    <tr><td><code>⏪</code></td><td>Rewind 10 seconds</td></tr>
    <tr><td><code>DISK SKIP</code></td><td>Toggle repeat/random track mode</td></tr>
    <tr><td><code>⏩</code></td><td>Fast forward 10 seconds</td></tr>
    <tr><td><code>⏸</code></td><td>Play/pause</td></tr>
    <tr><td><code>⏮</code></td><td>Jump to the beginning of the current track or to the previous track</td></tr>
    <tr><td><code>▶</code></td><td>Play/pause</td></tr>
    <tr><td><code>⏭</code></td><td>Jump to the next track</td></tr>
    <tr><td><code>⏹</code></td><td>Stop after current track</td></tr>
    <tr><th colspan=3>Samsung Smart TV remote control</th></tr>
    <tr><td></td><td><code>⏺</code></td><td>Play/pause</td></tr>
  </tbody>
</table>

## Deploy

Copy files from `/configurations` local folder to device
folder `/data/INTERNAL/ir_controller/configurations/`.

[phts np-01]: https://tsaryk.com/NP-01
[ir controller]: https://github.com/volumio/volumio-plugins-sources/tree/master/ir_controller
