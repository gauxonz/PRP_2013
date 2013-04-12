PRP_2013
========

PRP_piezoelectric_ceramics

This project is to design a circuit to drive piezoelectric ceramics.

requiremts:
<table border="1">
<tr>
<td>Control input</td>
<td>Output voltage</td>
<td>Average output current</td>
<td>Output impedance </td>
<td>Load type </td>
<td>Ripple,noise ,0 to 3kHz</td>
<td>Amplifier bandwidth </td>
</tr>
<tr>
<td>0 – (10 or 12) V </td>
<td> 0 – 120 V</td>
<td>Peak up to 3A</td>
<td>less than 5Ω</td>
<td>压电陶瓷 AE0505D16F Capacitor 1.4μ F</td>
<td>less than 5 mV RMS, less than 10 mV p−p</td>
<td>0- 3khz</td>
</tr>
</table>
文件说明：
----------------------------------------------------
<pre>
PRP_CreamPower.DsnWrk     altium designer 主工程文件</br>
PRP_CreamPower_PCB.PrjPCB altium designer PCB工程文件
./Schematics              原理图文件夹
./Lib                     库文件夹
./Lib/PA93.ckt            PA93 模拟库，由undergraduate project/apex amplifier spice lib/apexpoweropamps_0811-2/PA93.LIB
                          改后缀名而来，因为ad10只认.ckt
./LIb/APEXLINEAR.ckt      同上
./Lib/PA93.SchLib         PA93symbol及封装库，下不到，自己写的
</pre>
