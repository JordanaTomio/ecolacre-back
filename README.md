# EcoLacre

## CONTRATOS ##

### SolicitacaoFisica
Post - "/solicitacoes/fisica"

    String nome;
    String cpf;
    String telefone;
    Date dataNascimento;
    String email;
    String rg; //?

    String rendaFamiliarMedia;
    String endereco;
    String cidade;
    String uf;

    boolean estuda;
    boolean trabalha;
    
    boolean concordaComTermosDoProjeto;
    String razaoCadeiraDeRodas;
    
    int larguraCostasCm;
    int pesoKg;
    int quadrilCm;
    int alturaCm;
    int menorLarguraPortaCasaCm;
    int larguraAssentoCm;
    
    int responsavelNome;
    int responsavelTelefone;
    int responsavelEmail;

### SolicitacaoJuridica
Post - "/solicitacoes/juridica"

    String razaoSocial;
    String nomeFantasia;
    String cnpj;
    String endereco;
    String cidade;
    String telefone;
    String uf;
    String cep;
    String email;
    String atividadesDesempenhadas;
    String incentivoFinanceiro;
    String mediaPessoasBeneficiadasMensalmente;

    int qtdCadeiraRodasInstituicao;
    boolean cadeiraRodasSaoEmprestadas;
    String descricaoModeloCadeiraRodas;

    int responsavelNome;
    int responsavelTelefone;
    int responsavelEmail;

    boolean concordaComTermosDoProjeto;
    String razaoCadeiraDeRodas;