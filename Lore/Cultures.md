## Évolution des cultures
```mermaid
stateDiagram-v2
    Divin: Créationnisme
	state "Primordialisme" as Élémentaire
	state Élémentaire {
		Terran: Terrannisme
		Auran: Aurannisme
		Aquan: Aquannisme
		Ignan: Ignannisme
	}
	state "Aérianisme" as Aérien
	state Aérien {
        Direction LR
		Aarakocra: Avianisme
		Goliath: Tribalisme
	}
	state "Elfisme" as Elfe
	state Elfe {
		Sylvestre: Sylvestre
		HautElfe: Haut-Elfisme
		Drow: Drowisme
	}
	state "Humanisme" as Humain
	state Humain {
		Nécromancie: Nécromancie
		Manasie: Nomadisme
		Whitford: Nordisme
		Kinford: Empirisme
	}
    State Gobelinoïde {
        Gobelours: Druidisme Tribal
	    Gobelin: Gobelinisme Parasitique
	    Hobgobelin: Gobelinisme Tribal
    }
	Sylvain: Sylvanisme
	Dragon: Drakéisme
	Géant: Titanisme
	Démon : Abyssal
	Diable: Diabolisme
	Gnome: Gnomisme
	Halfelin: Demi-Humanisme
	Nain: Nanisme
	Orc: Chaotisme
	Souterrain: Souterranisme
	Aberration: Aberrations
	

	[*] --> Divin
	Divin --> Élémentaire
	
	Auran --> Dragon
	Ignan --> Démon
	Ignan --> Nain
	Aquan --> Elfe
	Terran --> Aberration
	Terran --> Géant
    Élémentaire --> Sylvain

	Géant --> Humain

	Dragon --> Aérien
	Dragon --> Elfe
	
	Démon --> Diable
	Démon --> Orc
	Démon --> Gobelinoïde
	Humain --> Hobgobelin
	Hobgobelin --> Gobelin
	Hobgobelin --> Gobelours

	Sylvain --> Elfe
	Sylvain --> Gobelours
	Sylvain --> Gnome

    Elfe --> Orc
	Gnome --> Halfelin
	Halfelin --> Gobelin
	
	Sylvestre --> Whitford
	Sylvestre --> HautElfe
	HautElfe --> Kinford
	HautElfe --> Drow
	Drow --> Nécromancie
	Drow --> Souterrain
    Nain --> Souterrain

	Manasie --> Kinford
	Kinford --> Nécromancie
	Whitford --> Nécromancie
	Nécromancie --> Aberration
```
## Langages
### Évolutions

```mermaid
stateDiagram-v2
    Divin: Celeste
	state "Primordial" as Élémentaire
	state Élémentaire {
		Terran: Terran
		Auran: Auran
		Aquan: Aquan
		Ignan: Ignan
	}
	state "Langues des plateaux" as Aérien
	state "Elfique" as Elfe
	state Elfe {
		Sylvestre: Sylvestre
		HautElfe: Haut-Elfe
		Drow: Elfique des profondeurs
	}
	state "Commun" as Humain
	state Humain {
		Nécromancie: Impérial Profond
		Manasie: Commercial planaire
		Whitford: Nordique
		Kinford: Impérial
	}
    Gobelinoïde
	Sylvain: Sylvain
	Dragon: Draconique
	Géant: Géant/Runique
	Démon : Abyssal
	Diable: Infernal
	Gnome: Gnome
	Halfelin: Halfelin
	Nain: Nain
	Orc: Orc
	Souterrain: Commun des profondeurs
	Aberration: Profond
	

	[*] --> Divin
	Divin --> Élémentaire
	
	Auran --> Dragon
	Ignan --> Démon
	Ignan --> Nain
	Aquan --> Elfe
	Terran --> Aberration
	Terran --> Géant
    Élémentaire --> Sylvain
    Sylvain --> Druidique

	Géant --> Kinford

	Dragon --> Aérien
	Dragon --> Elfe
	
	Démon --> Diable
	Démon --> Orc
	Humain --> Gobelinoïde

	Sylvain --> Elfe
	Sylvain --> Gnome

    Nain --> Orc
	Gnome --> Halfelin
	Halfelin --> Gobelinoïde
	
	Sylvestre --> HautElfe
	Elfe --> Humain
	HautElfe --> Drow
	Drow --> Souterrain
    Nain --> Souterrain

	Kinford --> Manasie
    Whitford --> Manasie
	Kinford --> Nécromancie
	Nécromancie --> Aberration
    Souterrain --> Aberration
```

### Équivalences
#### Humain
##### Commun
Commercial planaire — Français
##### Dialectes
Impérial — Espagnol
Nordique — Roumain
Impérial profond — Catalan

#### Famille du Géants
Géant — Hébreu
Nain — Arabe
Nain des collines — Matais
Gobelinoïde — Amharique
Duergar — Haoussa

#### Famille du Sylvain
Draconique — Chinois (Traditionnel)
Sylvain — Persan
Unseelie/Outremonde — Pachtô

##### Elfique
Elfique — Anglais %%(Urdu+Hindi)%%
Haut-Elfe — Irlandais
Sylvestre —  Gaélique (Écosse)
Drow — Gallois

##### Dérivés elfiques
Orc — Kurde (Kurmanji)
Yuan-Ti — Japonais
Halfling — Suedois

##### Gnome
Gnome — Polonais
Gnome des Forêts — Ukrainien
Gnome des Rochers — Polonais
Svirfneblin — Biélorusse

Commun des profondeurs — LSF/Russe
Celeste — Grec

#### Famille de l'Infernal
Infernale — Telugu
Abyssale — Tamoul
Gnoll — Kannada

#### Famille du primordial
Primordial — Javanais
Aquan — Hawaiian
Auran — Indonesian
Ignan — Sundanese
Terran — Filipino

#### Autres
Profond — Espéranto