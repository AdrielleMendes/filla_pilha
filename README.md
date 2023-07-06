# filla_pilha

class Pilha:
    def __init__(self):
        self.pilha =[]

    def push(self, item):
        self.pilha.append(item)

    def pop(self):
        if not self.lista.esta_vazio():
            valor_topo = self.lista.inicio.valor
            self.lista.remove(valor_topo)
            return valor_topo
        else:
            print("A pilha está vazia")
            return None

def recupera_indice(self,index):
    if 0 <=index<len(self.pilha):
       return self.pilha[index]
    else:
        return 1


def  indice_de(self, item):
        if item in self.pilha:
           return self.pilha.index(Pilha)
        else:
           return 1

def esta_vazia(self):
        return len(self.pilha) == 0

def tamanho(self):
        return len(self.pilha)

def procura(self, item) -> bool:
        if item in self.pilha:
            return True
        else:
          return False
def limpa(self):
        self.pilha=[]
        pass
def inserir_inicio(self,valor):
        if self.pilha is None:
            self.pilha = (valor)
        else:
            novoNo = (valor)
            novoNo.set_proximo(self.inicio)
            self.pilha = novoNo
def inserir_fim(self, valor):
        if self.pilha is None:
            self.pilha = (valor)
        else:
            novoNo = (valor)
            aux = self.pilha
            while aux.get_proximo() is not None:
                aux = aux.get_proximo()
            aux.set_proximo(novoNo)

def remove(self, item):
        if item in self.pilha:
            self.pilha.remove(item)
            print("item removido com sucesso")  
        else:
            print("o item não existi na lista ")
        pass


class fila :
    def __init__(self):
        self.lista =()

    def enfileirar(self, item):
        self.lista.inserir_fim(item)

    def desenfileirar(self):
        if not self.lista.esta_vazio():
            return self.lista.remove_indice(0)
        else:
            print("A fila está vazia")
            return None
    def recupera_indice(self, index):
    
        if 0 <= index <len(self.valor):
            return self.v[index]
        else:
            return 1

    def esta_vazia(self):
        return len(self.fila) == 0

    def tamanho(self):
        return len(self.fila)

    def procura(self, item):
        return item in self.fila

    def limpa(self):
        self.fila = []
    
    def indice_de(self, item):
        if item in self.fila:
            return self.fila.index(item)
        else:
            return -1

    def remove(self, item):
        if item in self.fila:
            self.fila.remove(item)
            print("Item removido com sucesso")
        else:
            print("O item não existe na fila") 

    def inserir_inicio(self, valor):
        self.fila.insert(0, valor)  


    def inserir_fim(self, valor):
        self.fila.append(valor)    
