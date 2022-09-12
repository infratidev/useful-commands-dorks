[![Blog](https://img.shields.io/website?down_color=blue&down_message=infrati.dev&label=Blog&logo=ghost&logoColor=green&style=for-the-badge&up_color=blue&up_message=infrati.dev&url=https%3A%2F%2Finfrati.dev)](https://infrati.dev)

### 📋 infratidev
## Useful linux commands

### Substituição recursiva com uma string de pesquisa

~~~
grep -rl 'String' ./* | xargs sed -i 's/String/Replace/g'
~~~

### Mover recursivamente arquivos dado uma string de pesquisa

~~~
for i in ./*string*;do mv -- "$i" "${i//string/replace}";done
~~~




<br>

[![Blog](https://img.shields.io/website?down_color=blue&down_message=infrati.dev&label=Blog&logo=ghost&logoColor=green&style=for-the-badge&up_color=blue&up_message=infrati.dev&url=https%3A%2F%2Finfrati.dev)](https://infrati.dev)




