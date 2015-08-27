 nvram get custom_clientlist | sed -n -e 's/>>/\n/g ; s/<//g
; s/>/ /gp'
