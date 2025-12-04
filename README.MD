# Projeto: Site com 3 Páginas – Flexbox x Grid

#  Estrutura do Projeto
- Página 1: Filmes (usando **Flexbox**)
- Página 2: Livros (usando **Grid**)
- Página 3: Músicas (layout livre com colunas)

---

#  Diferença entre Flexbox e Grid

# Flexbox
Flexbox é um sistema de layout **unidimensional**:
- Organiza elementos em **linha** ou **coluna**
- Ideal para listas, barras, galerias simples

**Use flexbox quando:**
- Precisa alinhar itens facilmente
- O layout flui em uma única direção

**Aplicação no projeto:**  
Usado para organizar os **cartazes dos filmes**, formando uma galeria flexível.

---

# CSS Grid
CSS Grid é um sistema de layout **bidimensional**:
- Trabalha com **linhas e colunas ao mesmo tempo**
- Ideal para páginas mais estruturadas

**Use Grid quando:**
- Precisa criar grades organizadas
- O layout depende de proporções e alinhamento preciso

**Aplicação no projeto:**  
Usado para montar a grade de **livros**, formando 5 colunas fixas.

---

# Terceira Página
A página de músicas usa:
- Colunas CSS (`columns`)
- Sombreamento
- Layout livre e alternativo

---

# Tecnologias Usadas
- HTML5
- CSS3 (Flexbox, Grid, Columns)
- Imagens externas (google distintas👀)

---

# 👨‍🎓 Autor:David
Projeto desenvolvido como atividade escolar.

--------------------------------------------------------------------------------------------------------------------------------------------
<!-- Nota de curiosidade: -->

<script>
// atualiza o ano no rodapé automaticamente
document.getElementById('year').textContent = new Date().getFullYear();
</script>
    