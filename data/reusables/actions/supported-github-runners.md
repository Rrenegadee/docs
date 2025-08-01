### Standard {% data variables.product.prodname_dotcom %}-hosted runners for public repositories

For public repositories, jobs using the workflow labels shown in the table below will run on virtual machines with the associated specifications. The use of these runners on public repositories is free and unlimited.

<table style="width:100%">
  <thead>
    <tr>
      <th scope="col"><b>Virtual Machine</b></th>
      <th scope="col"><b>Processor (CPU)</b></th>
      <th scope="col"><b>Memory (RAM)</b></th>
      <th scope="col"><b>Storage (SSD)</b></th>
      <th scope="col"><b>Architecture</b></th>
      <th scope="col"><b>Workflow label</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Linux</td>
      <td>4</td>
      <td>16 GB</td>
      <td>14 GB</td>
      <td> x64 </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2404-Readme.md">ubuntu-latest</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2404-Readme.md">ubuntu-24.04</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2204-Readme.md">ubuntu-22.04</a></code>
      </td>
    </tr>
    <tr>
      <td>Windows</td>
      <td>4</td>
      <td>16 GB</td>
      <td>14 GB</td>
      <td> x64 </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/windows/Windows2022-Readme.md">windows-latest</a></code>,
         <code><a href="https://github.com/actions/runner-images/blob/main/images/windows/Windows2025-Readme.md">windows-2025</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/windows/Windows2022-Readme.md">windows-2022</a></code>
      </td>
    </tr>
    <tr>
      <td>Linux [Public preview]</td>
      <td>4</td>
      <td>16 GB</td>
      <td>14 GB</td>
      <td> arm64 </td>
      <td>
        <code><a href="https://github.com/actions/partner-runner-images/blob/main/images/arm-ubuntu-24-image.md">ubuntu-24.04-arm</a></code>,
        <code><a href="https://github.com/actions/partner-runner-images/blob/main/images/arm-ubuntu-22-image.md">ubuntu-22.04-arm</a></code>
      </td>
    </tr>
    <tr>
      <td>Windows [Public preview]</td>
      <td>4</td>
      <td>16 GB</td>
      <td>14 GB</td>
      <td>arm64</td>
      <td>
        <code><a href="https://github.com/actions/partner-runner-images/blob/main/images/arm-windows-11-image.md">windows-11-arm</a></code>
      </td>
    </tr>
    <tr>
      <td>macOS</td>
      <td>4</td>
      <td>14 GB</td>
      <td>14 GB</td>
      <td> Intel </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-13-Readme.md">macos-13</a></code>
      </td>
    </tr>
    <tr>
      <td>macOS</td>
      <td>3 (M1)</td>
      <td>7 GB</td>
      <td>14 GB</td>
      <td> arm64 </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-14-Readme.md">macos-latest</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-14-Readme.md">macos-14</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-15-Readme.md">macos-15</a></code>
      </td>
    </tr>
  </tbody>

</table>

>[!NOTE] The arm64 Linux and Windows runners are in {% data variables.release-phases.public_preview %} and subject to change.

### Standard {% data variables.product.prodname_dotcom %}-hosted runners for {% ifversion ghec %}internal and{% endif %} private repositories

For {% ifversion ghec %}internal and{% endif %} private repositories, jobs using the workflow labels shown in the table below will run on virtual machines with the associated specifications. These runners use your {% data variables.product.prodname_dotcom %} account's allotment of free minutes, and are then charged at the per minute rates. For more information, see [AUTOTITLE](/billing/managing-billing-for-github-actions/about-billing-for-github-actions#per-minute-rates).

<table style="width:100%">
  <thead>
    <tr>
      <th scope="col"><b>Virtual Machine</b></th>
      <th scope="col"><b>Processor (CPU)</b></th>
      <th scope="col"><b>Memory (RAM)</b></th>
      <th scope="col"><b>Storage (SSD)</b></th>
      <th scope="col"><b>Architecture</b></th>
      <th scope="col"><b>Workflow label</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Linux</td>
      <td>2</td>
      <td>7 GB</td>
      <td>14 GB</td>
      <td> x64 </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2404-Readme.md">ubuntu-latest</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2404-Readme.md">ubuntu-24.04</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2204-Readme.md">ubuntu-22.04</a></code>
      </td>
    </tr>
    <tr>
      <td>Windows</td>
      <td>2</td>
      <td>7 GB</td>
      <td>14 GB</td>
      <td> x64 </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/windows/Windows2022-Readme.md">windows-latest</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/windows/Windows2025-Readme.md">windows-2025</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/windows/Windows2022-Readme.md">windows-2022</a></code>
      </td>
    </tr>
    <tr>
      <td>macOS</td>
      <td>4</td>
      <td>14 GB</td>
      <td>14 GB</td>
      <td> Intel </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-13-Readme.md">macos-13</a></code>
      </td>
    </tr>
    <tr>
      <td>macOS</td>
      <td>3 (M1)</td>
      <td>7 GB</td>
      <td>14 GB</td>
      <td> arm64 </td>
      <td>
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-14-Readme.md">macos-latest</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-14-Readme.md">macos-14</a></code>,
        <code><a href="https://github.com/actions/runner-images/blob/main/images/macos/macos-15-Readme.md">macos-15</a></code>
      </td>
    </tr>
  </tbody>
</table>

{% ifversion ghec %}

> [!NOTE] {% data reusables.actions.macos-unavailable-ghecom %}

{% endif %}
