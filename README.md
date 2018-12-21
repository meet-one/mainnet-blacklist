# mainnet-blacklist

Step 1: add these accounts to config.ini of nodeos
```
actor-blacklist = blacklistmee
actor-blacklist = ge2dmmrqgene
actor-blacklist = gu2timbsguge
actor-blacklist = ge4tsmzvgege
actor-blacklist = gezdonzygage
actor-blacklist = ha4tkobrgqge
actor-blacklist = gq4dkmzzhege
actor-blacklist = gu2teobyg4ge
actor-blacklist = gq4demryhage
actor-blacklist = q4dfv32fxfkx
actor-blacklist = ktl2qk5h4bor
actor-blacklist = haydqnbtgene
actor-blacklist = g44dsojygyge
actor-blacklist = guzdonzugmge
actor-blacklist = ha4doojzgyge
actor-blacklist = gu4damztgyge
actor-blacklist = haytanjtgige
actor-blacklist = exchangegdax
actor-blacklist = cmod44jlp14k
actor-blacklist = 2fxfvlvkil4e
actor-blacklist = yxbdknr3hcxt
actor-blacklist = yqjltendhyjp
actor-blacklist = pm241porzybu
actor-blacklist = xkc2gnxfiswe
actor-blacklist = ic433gs42nky
actor-blacklist = fueaji11lhzg
actor-blacklist = w1ewnn4xufob
actor-blacklist = ugunxsrux2a3
actor-blacklist = gz3q24tq3r21
actor-blacklist = u5rlltjtjoeo
actor-blacklist = k5thoceysinj
actor-blacklist = ebhck31fnxbi
actor-blacklist = pvxbvdkces1x
actor-blacklist = oucjrjjvkrom
actor-blacklist = neverlandwal
actor-blacklist = tseol5n52kmo
actor-blacklist = potus1111111
actor-blacklist = craigspys211
actor-blacklist = eosfomoplay1
actor-blacklist = wangfuhuahua
actor-blacklist = guytqmbuhege
actor-blacklist = huobldeposit
actor-blacklist = gm3dcnqgenes
actor-blacklist = gm34qnqrepqt
actor-blacklist = gt3ftnqrrpqp
actor-blacklist = gtwvtqptrpqp
actor-blacklist = gm31qndrspqr
actor-blacklist = lxl2atucpyos
actor-blacklist = g4ytenbxgqge
actor-blacklist = jinwen121212
actor-blacklist = ha4tomztgage
actor-blacklist = my1steosobag
actor-blacklist = iloveyouplay
actor-blacklist = eoschinaeos2
actor-blacklist = eosholderkev
actor-blacklist = dreams12true
actor-blacklist = imarichman55
actor-blacklist = gizdcnjyg4ge
actor-blacklist = gyzdmmjsgige
actor-blacklist = guzdanrugene
actor-blacklist = earthsop1sys
actor-blacklist = refundwallet
actor-blacklist = jhonnywalker
actor-blacklist = alibabaioeos
actor-blacklist = whitegroupes
actor-blacklist = 24cryptoshop
actor-blacklist = minedtradeos
actor-blacklist = gizdkmjvhege
```


Step 2: verify accounts
```
grep actor-black config.ini | grep -v "#" | sort | tr -d " " | sha256sum
# the hash of latest blacklist
# 1adf65d8d9272f1634240a0e057910d5c276ede1aa96463b8ad2fa1af62e47ef
```

Step 3: restart nodeos

for more information about blacklist, please visit [https://www.bloks.io/blacklist](https://www.bloks.io/blacklist)


