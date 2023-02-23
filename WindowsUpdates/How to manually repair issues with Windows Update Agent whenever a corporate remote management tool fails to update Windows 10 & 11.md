# How to manually repair issues with Windows Update Agent whenever a corporate remote management tool fails to update Windows 10 & 11
The following steps are still relevant on WIndows 11. However, all examples will be provided for the last supported version of Windows 10, as of February 23th, 2023; the last Win10 build released is **21H2**.

<details>
<summary>Background relevant information...</summary>
- Servicing Stack Updates are shipped by Microsoft separately from the Cumulative Updates because they modify **side-by-side assemblies** required to install Windows Updates that are located on the Windows Component Store (on path **C:\Windows\WinSxS** by default).  
_Sources:_ 
-- https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/manage-the-component-store?view=windows-11

</details>


