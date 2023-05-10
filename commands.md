


# OFte brukte kommandoer

Beste cheat sheet: https://www.stationx.net/nmap-cheat-sheet/



## Vis hjelpetekst

```shell
nmap
```

## Enkel scan av subnet

```shell
nmap -vv 10.2.2.0/24
```

## Ignore ping

For å få nmap til å scanne et target, selv om det ikke svarer på ping, må vi bruke `Pn` som argument

```shell
-Pn
``` 

## Verbose output

For å få nmap til å skrive ut mer output når den scanner, kan vi legge til en eller flere `-v` argumenter. jo flere vi legger til, jo mer info vil nmap skrive ut under scan.

```shell
-v
```

## Aggressive scan av target

```shell
nmap -A -T4 10.0.0.22 -vv
```

