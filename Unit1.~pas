unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

// <- Essas duas barras sao usadas para realizar um comentario que nao interferem no codigo
// Usadas para observação e para ajudar no entendimento do código
// Podem ser usadas com as duas barras ou

{
  com duas chaves - Note que as letras ficam da cor azul no delphi o que as diferencia do codigo padrao
}

// Procedure é um bloco de comandos que montamos para que faça determinada ação - nesse caso irá nos ajudar a
// aprender os comandos básicos do delphi resumidamente, e ela ocorre ao clicar do botao
procedure TForm1.Button1Click(Sender: TObject);
begin
  // Abre um console;
  AllocConsole();

  // Imprime algo(Texto, número, etc) no console
  Write('"Ola mundo" vai permanecer na mesma linha: ');
  Writeln('Ola Mundo! ');
  
  // Imprime algo(Texto, número, etc) no console e quebra a linha
  Writeln('"Ola mundo" vai comecar na linha de baixo: ');
  Writeln('Ola Mundo! ');

end;

procedure TForm1.Button2Click(Sender: TObject);
// Variáveis criadas para guardar valores uteis para o programador
// Elas podem ter varios tipos dentre eles Integer, String, Char, Boolean, Date, Float;
var
  // Declaramos com o nome e o seu tipo
  Nome: string;
begin
   AllocConsole();

  // Vamos pedir para alguem informar o nome
  Write('Escreva seu nome:');

  // Agora vamos permitir que a pessoa insira o nome e vamos guardar seu valor na variavel Nome
  Read(Nome);
  {
    Guardar um valor numa variável é chamado de atribuiçao e comumente dizemos que a "variavel recebe um valor"
    no caso do Read() a atribuição é indireta pois nao vemos como isso ocorre no proximo botao veremos uma atribuição direta
  }

  // Vamos agora imprimir uma mensagem para a pessoa com o nome dela da mensagem fora do console
  ShowMessage('Olá '+ Nome + ' Bem vindo ao Delphi!');
end;

procedure TForm1.Button3Click(Sender: TObject);
begin
  AllocConsole();
end;

end.
