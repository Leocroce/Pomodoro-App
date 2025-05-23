![Pomodoro Timer Screenshot](assets/screenshot.png)

# Pomodoro Timer

Um temporizador Pomodoro simples feito em Python com interface gráfica (Tkinter) e alerta sonoro (pygame).

## Pré-requisitos

- Python 3.10 instalado.  
  [Download Python 3.10](https://www.python.org/downloads/release/python-3100/)
- pip atualizado (`python -m pip install --upgrade pip`)

## Instalação

1. Clone este repositório:
    ```
    git clone https://github.com/Leocroce/Pomodoro-App.git
    cd Pomodoro-App
    ```

2. Instale as dependências:
    ```
    pip install -r requirements.txt
    ```

3. Certifique-se de que os arquivos `tomato.png` e `notification-alert-1-331727.mp3` estão na pasta `assets/`.

## Como usar

Execute o programa:

python main.py

## Como gerar o executável (.exe) usando auto-py-to-exe

### 1. Instale o auto-py-to-exe

No terminal, execute:

```bash
pip install auto-py-to-exe
```

Se você tiver mais de uma versão do Python instalada, pode usar:

```bash
python -m pip install auto-py-to-exe
```


---

### 2. Abra o auto-py-to-exe

No terminal, execute:

```bash
auto-py-to-exe
```

Se não funcionar, tente:

```bash
python -m auto_py_to_exe
```

Isso abrirá uma interface gráfica.

---

### 3. Configure a conversão na interface gráfica

- **Script Location**: Clique em "Browse" e selecione o arquivo `main.py` do seu projeto.
- **Onefile**: Marque esta opção se quiser um único arquivo `.exe`. Deixe desmarcado para criar uma pasta com vários arquivos.
- **Console Window**:
    - Se seu programa é gráfico (Tkinter), selecione "Window Based".
    - Se for terminal, selecione "Console Based".
- **Additional Files**:
    - Clique em "Add Folder" e selecione a pasta `assets/` para garantir que as imagens e sons sejam incluídos no executável.
- **Output Directory**: Escolha a pasta onde o executável será salvo (por padrão, será criada uma pasta `output`).
- (Opcional) Defina um ícone para seu executável na opção "Icon".

---

### 4. Gere o executável

- Clique no botão azul "Convert .py to .exe" no final da interface.
- Aguarde o processo terminar. O executável estará na pasta `output` criada no seu projeto.

---

### 5. Teste o executável

- Vá até a pasta `output` e execute o arquivo `.exe` gerado para testar se está funcionando corretamente.

---

#### Resumo dos comandos

```bash
pip install auto-py-to-exe
auto-py-to-exe
# ou, se necessário:
python -m auto_py_to_exe
```


---

#### Observações

- Se o executável não rodar em outro computador, certifique-se de copiar também a pasta `assets/` junto do `.exe` se não usou a opção "Onefile" ou se os arquivos não foram corretamente incluídos.
- Para mais detalhes ou problemas, consulte a [documentação oficial do auto-py-to-exe](https://pypi.org/project/auto-py-to-exe/).

