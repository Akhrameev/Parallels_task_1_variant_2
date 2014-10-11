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
</table>
