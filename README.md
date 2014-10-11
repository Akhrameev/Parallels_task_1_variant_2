Parallels_task_1_variant_2
==========================

Solution of Dirihlet task

[Task (rus: pdf)](Lab1_2.pdf)

<table>
  <tr>
    <th colspan="12">256x256x256</th>
  </tr>
  <tr>
    <td colspan="2">Sequentional run (-O2)</td>
    <td colspan="2">OpenMP run (-O2) n=1</td>
    <td colspan="2">OpenMP run (-O2) n=2</td>
    <td colspan="2">OpenMP run (-O2) n=4</td>
    <td colspan="2">OpenMP run (-O2) n=8</td>
    <td colspan="2">OpenMP run (-O2) n=16</td>
  </tr>
  <tr>
    <td>68.566s</td>
    <td>S=789140100.274497</td>
    <td>66.3721s</td>
    <td>S=789140100.274497</td>
    <td>34.4107s</td>
    <td>S=789140100.274047</td>
    <td>18.8399s</td>
    <td>S=789140123.383595</td>
    <td>9.70675s</td>
    <td>S=789118751.258036</td>
    <td>7.67158s</td>
    <td>S=788963797.919279</td>
  </tr>
  <tr>
    <td>66.3202s</td>
    <td>S=789140100.274497</td>
    <td>65.6133s</td>
    <td>S=789140100.274497</td>
    <td>36.2631s</td>
    <td>S=789140100.274047</td>
    <td>18.3051s</td>
    <td>S=789140123.383596</td>
    <td>9.72643s</td>
    <td>S=789118751.258036</td>
    <td>7.2472s</td>
    <td>S=788899022.536085</td>
  </tr>
  <tr>
    <th colspan="12">384x384x384</th>
  </tr>
  <tr>
    <td>399.79s</td>
    <td>S=4441160348.874235</td>
    <td>239.098s</td>
    <td>S=4441160348.874235</td>
    <td>120.566s</td>
    <td>S=4441160348.869160</td>
    <td>62.7336s</td>
    <td>S=4441160348.891895</td>
    <td>35.4974s</td>
    <td>S=4441160218.529609</td>
    <td></td>
    <td>S=</td>
  </tr>
  <tr>
    <th colspan="12">512x512x512</th>
  </tr>
  <tr>
    <td>672.965s</td>
    <td>S=14780896925.508070</td>
    <td>577.393s</td>
    <td>S=14780896925.508070</td>
    <td>283.429s</td>
    <td>S=14780896925.734921</td>
    <td>163.6s</td>
    <td>S=14780896925.873995</td>
    <td>87.6649s</td>
    <td>S=14780897028.088871</td>
    <td></td>
    <td>S=</td>
  </tr>
</table>

[Results (rus: pdf)](Results.pdf)

[Graph for cells](graph_cells.png?raw=true)

[Graph for cpus](graph_cpus.png?raw=true)
