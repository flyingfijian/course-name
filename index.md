# This is a header for the index.md file


- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world






![Image of the Greatest 7's Rugby World Player](https://c8.alamy.com/comp/HXMYMW/waisale-serevi-fiji-ru-manchester-england-07-august-2002-HXMYMW.jpg)




```

$templateName = 'template'

$esxName = 'esx'

$dsName = 'ds'

$template = Get-Template -Name $templateName

$ds = Get-Datastore -Name $dsName

$esx = Get-VMHost -Name $esxName

$vm = New-VM -Template $template -Name stressTest -VMHost $esx -Datastore $ds -DiskStorageFormat Thin |

Set-VM -NumCpu 2 -MemoryGB 4 -Confirm:$false

Get-HardDisk -VM $vm | Set-HardDisk -CapacityGB 100

Start-VM -VM $vm -Confirm:$false

```






