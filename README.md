# Public-private-settings-
A public-private data settings with PHP
Codes:


<?php
    private $id = 1;
    private $name = "Uygar";
    private $surname = "Ayhan";
    private $number = 123456789;
    public function getId(){
        return $this->id;
    }
    public function getName(){
        return $this->name;
    }
    public function getSurname(){
        return $this->surname;
    }
    public function getNumber(){
        return $this->number;
    }
    echo function getId();
    echo function getName();
    echo function getSurname();
    echo function getNumber();
?>
