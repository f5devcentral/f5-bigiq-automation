Installation instructions
-------------------------

Download the script on Active BIG-IQ CM.

```
bash
mkdir /shared/scripts
cd /shared/scripts
curl https://raw.githubusercontent.com/f5devcentral/f5-big-iq-pm-team/master/f5-bigiq-dcd-health-checks/f5_dcd_health_checks.sh > f5_dcd_health_checks.sh
chmod +x f5_dcd_health_checks.sh
```

Usage
-----

The script needs to be executed on *Active BIG-IQ CM*.

```
cd /shared/scripts
./f5_dcd_health_checks.sh [<BIG-IQ DCD sshuser>]
```

BIG-IQ DCD ssh user is optional. **root** user is used by default if nothing is specified.