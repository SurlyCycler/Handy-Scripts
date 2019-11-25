# Handy-Scripts
A corrected version of HPLIP driver for hp-envy_5000_series
it corrects for cups 2.30 error cannot copy ppd

create a file on your home directory
$ nano hp-envy_5000_series.ppd.
copy and paste the script inside 

sudo cp your/file/location/hp-envy_5000_series.ppd  /etc/cups/ppd/hp-envy_5000_series.ppd

chmod 0640 /etc/cups/ppd/hp-envy_5000_series.ppd

When cups is looking for a ppd you can specify this file and all will work
