;; This buffer is for text that is not saved, and for Lisp evaluation.
;; To create a file, visit it with ‘C-x C-f’ and enter text in its buffer.

# Public GPG keys from TAILSIT

## Lars Kielhorn

### Fingerprints
```
pub   rsa4096 2025-03-12 [C]
      2129 A9FC B408 1B4F 2158  E46B BCBE 1BAB CFC2 B3D2
uid           [ultimate] Lars Kielhorn (TAILSIT GMBH) <lars.kielhorn@tailsit.com>
uid           [ultimate] info@tailsit.com
uid           [ultimate] office@tailsit.com
sub   rsa4096 2025-03-12 [S] [expires: 2028-03-11]
      9FCE 3F65 1106 9B0A D8A9  CD9A 611E 88FE 440E 85AD
sub   rsa4096 2025-03-12 [E] [expires: 2028-03-11]
      AB68 2704 FCA7 0D8E 5FE9  CF8E DD49 FC4F 9CAC E536
sub   rsa4096 2025-03-12 [A] [expires: 2028-03-11]
      7CA8 96D2 E0C2 D129 66E7  5223 38E3 14BD 17C0 3E8F
```

### Download from keyservers
```gpg --keyserver keys.openpgp.org --recv-keys BCBE1BABCFC2B3D2```    
or    
```gpg --keyserver keyserver.ubuntu.com --recv-keys BCBE1BABCFC2B3D2```

### Manually fetch the key
If the keyserver is unreachable, you can manually download the key:    
```curl -fsSL "https://keys.openpgp.org/vks/v1/by-fingerprint/2129A9FCB4081B4F2158E46BBCBE1BABCFC2B3D2" | gpg --import```    
or    
```curl -fsSL "https://keyserver.ubuntu.com/pks/lookup?op=get&search=0xBCBE1BABCFC2B3D2" | gpg --import```    

### Download from Github
Fetch ```lk-pub.key``` from this repository.
