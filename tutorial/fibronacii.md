# Fibronacii

Barisan Fibonacci merupakan baris yang berawal dari 0 dan 1, kemudian angka berikutnya didapatkan dengan cara menambahkan kedua bilangan yang berurutan sebelumnya. Dengan aturan ini, maka barisan bilangan Fibonacci yang pertama adalah:

```text
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377
```

Deret fibronaci di definisikan dengan fungsi dasar berikut:

```javascript
f(1) = 0
f(2) = 1
f(x) = f(x-1) + f(x-2)
```

implementasi dari fungsi di atas akan berbentuk seperti ini:

{% tabs %}
{% tab title="Python" %}
```python
def fib (n:int): 
    if (n == 1) fib = 0
    if (n == 2) fib = 1
    fib = fib(n - 1) + fib(n-2)
```
{% endtab %}

{% tab title="C\#" %}
```javascript
int fib(int n){

    if (n == 1) return 0;
    if (n == 2) return 1;

    return fib(n-1) + fib(n-2);
}
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Ini hanya berupa fungsi, jangan lupa di panggil pada kode utama.
{% endhint %}

