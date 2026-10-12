# Thermal-Headroom-
```[user@localhost ~]$ sudo nvme smart-log /dev/nvme0n1 
Smart Log for NVME device:nvme0n1 namespace-id:ffffffff
critical_warning			: 0
temperature				: 84 °F (302 K)
available_spare				: 100%
available_spare_threshold		: 5%
percentage_used				: 0%
endurance group critical warning summary: 0
Data Units Read				: 104502096 (53.51 TB)
Data Units Written			: 101811833 (52.13 TB)
host_read_commands			: 48331630
host_write_commands			: 49852656
controller_busy_time			: 1148
power_cycles				: 353
power_on_hours				: 3009
unsafe_shutdowns			: 262
media_errors				: 0
num_err_log_entries			: 2046
Warning Temperature Time		: 0
Critical Composite Temperature Time	: 0
Thermal Management T1 Trans Count	: 6
Thermal Management T2 Trans Count	: 3
Thermal Management T1 Total Time	: 39920
Thermal Management T2 Total Time	: 11624
[user@localhost ~]$ sudo nvme id-ctrl /dev/nvme0n1 
NVME Identify Controller:
vid       : 0x1987
ssvid     : 0x1987
sn        : 511221129056000360  
mn        : DIGISTOR 2TB                            
fr        : ECPG13.0
rab       : 1
ieee      : 0a2a33
cmic      : 0
mdts      : 9
cntlid    : 0x1
ver       : 0x10300
rtd3r     : 0x989680
rtd3e     : 0x989680
oaes      : 0x200
ctratt    : 0x2
rrls      : 0
cntrltype : 0
fguid     : 00000000-0000-0000-0000-000000000000
crdt1     : 0
crdt2     : 0
crdt3     : 0
nvmsr     : 0
vwci      : 0
mec       : 0
oacs      : 0x7
acl       : 3
aerl      : 3
frmw      : 0x12
lpa       : 0x8
elpe      : 62
npss      : 4
avscc     : 0x1
apsta     : 0x1
wctemp    : 348
cctemp    : 353
mtfa      : 100
hmpre     : 0
hmmin     : 0
tnvmcap   : 2048408248320
unvmcap   : 0
rpmbs     : 0
edstt     : 0
dsto      : 0
fwug      : 1
kas       : 0
hctma     : 0x1
mntmt     : 313
mxtmt     : 343
sanicap   : 0
hmminds   : 0
hmmaxd    : 0
nsetidmax : 0
endgidmax : 0
anatt     : 0
anacap    : 0
anagrpmax : 0
nanagrpid : 0
pels      : 0
domainid  : 0
megcap    : 0
tmpthha   : 0
sqes      : 0x66
cqes      : 0x44
maxcmd    : 256
nn        : 1
oncs      : 0x5d
fuses     : 0
fna       : 0
vwc       : 0x1
awun      : 255
awupf     : 0
icsvscc   : 1
nwpc      : 0
acwu      : 0
ocfs      : 0
sgls      : 0
mnan      : 0
maxdna    : 0
maxcna    : 0
oaqd      : 0
subnqn    : 
ioccsz    : 0
iorcsz    : 0
icdoff    : 0
fcatt     : 0
msdbd     : 0
ofcs      : 0
ps      0 : mp:10.73W operational enlat:0 exlat:0 rrt:0 rrl:0
            rwt:0 rwl:0 idle_power:- active_power:-
            active_power_workload:-
ps      1 : mp:7.69W operational enlat:0 exlat:0 rrt:1 rrl:1
            rwt:1 rwl:1 idle_power:- active_power:-
            active_power_workload:-
ps      2 : mp:6.18W operational enlat:0 exlat:0 rrt:2 rrl:2
            rwt:2 rwl:2 idle_power:- active_power:-
            active_power_workload:-
ps      3 : mp:0.0490W non-operational enlat:2000 exlat:2000 rrt:3 rrl:3
            rwt:3 rwl:3 idle_power:- active_power:-
            active_power_workload:-
ps      4 : mp:0.0018W non-operational enlat:25000 exlat:25000 rrt:4 rrl:4
            rwt:4 rwl:4 idle_power:- active_power:-
            active_power_workload:-
[user@localhost ~]$ ```
