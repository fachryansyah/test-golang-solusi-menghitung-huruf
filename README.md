# Solusi 1 : Menghitung huruf Hidup & Mati
Code untuk jawaban solusi 1 "Buat fungsi sederhana untuk menghitung jumlah huruf hidup dan huruf mati dari suatu kalimat"

## Instalasi
### Menginstall module
```sh
$ go get github.com/fachryansyah/test-golang-solusi-menghitung-huruf
```

### Menggunakan Module
```go
package main

import "testing"
import "github.com/fachryansyah/test-golang-solusi-menghitung-huruf"

func TestModule(test *testing.T)  {
	vocal, consonant := CountWord("omama")
	if vocal != 2 && consonant != 2 {
		test.Errorf("Count function was error, want(consonant: %d, vocal: %d) got(consonant: %d, vocal: %d)", 2, 2, consonant, vocal)
	}
}

```
