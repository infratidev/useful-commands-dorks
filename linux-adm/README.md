[![Blog](https://img.shields.io/website?down_color=blue&down_message=infrati.dev&label=Blog&logo=ghost&logoColor=green&style=for-the-badge&up_color=blue&up_message=infrati.dev&url=https%3A%2F%2Finfrati.dev)](https://infrati.dev)

### 📋 infratidev
## Useful linux commands

### 1. Substituição recursiva com uma string de pesquisa

~~~
grep -rl 'String' ./* | xargs sed -i 's/String/Replace/g'
~~~

### 2. Renomear arquivos dado uma string de pesquisa

~~~
for i in ./*string*;do mv -- "$i" "${i//string/replace}";done
~~~

### 3. Cópia utilizando find dado uma string de pesquisa para um diretório de destino 

~~~
cp -p $(find ./* -name '*string*') dir/
~~~

### 4. Instanciando um servidor web em python na porta 80

~~~
python3 -m http.server 80
~~~


<br>

[![Blog](https://img.shields.io/website?down_color=blue&down_message=infrati.dev&label=Blog&logo=ghost&logoColor=green&style=for-the-badge&up_color=blue&up_message=infrati.dev&url=https%3A%2F%2Finfrati.dev)](https://infrati.dev)




