$usuarios = [
    [
        "nome" => "Reginaldo",
        "sobrenome" => "Santos",
        "perfil" => "Administrativo"
    ],
    [
        "nome" => "Brunno",
        "sobrenome" => "Yokoyama",
        "perfil" => "Administrativo"
    ],
    [    "nome" => "Alex",
        "sobrenome" => "Silva",
        "perfil" => "Desenvolvedor"
    ],
];
     function printarAdm($usuarios){
        foreach($usuarios as $usuario){
            if($usuario["perfil"] == "Desenvolvedor"){
                echo "{$usuario["nome"]} {$usuario["sobrenome"]}\n";
            }
        }
     }
     printarAdm($usuarios);
?>
