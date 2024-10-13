flowchart TD
    A("fa:fa-calendar Réservation d'activités") --> B("fa:fa-users Utilisateur") & C("fa:fa-user-shield Administrateur")
    B --> D("fa:fa-paper-plane Soumettre une demande")
    D --> E{"Demande de réservation"}
    E -- Approbation --> C
    C -- Accepter --> F("fa:fa-check-circle Confirmer la réservation")
    C -- Rejeter --> G("fa:fa-times-circle Rejeter la réservation")
    F --> H("fa:fa-table Tableau de bord")
    G --> H
    H --> I("fa:fa-pencil-alt Modifier une réservation") & J("fa:fa-trash Annuler une réservation") & K("fa:fa-info-circle Afficher les détails")

    style A color:#FFFFFF, fill:#007BFF, stroke:#007BFF
    style B color:#FFFFFF, fill:#28A745, stroke:#28A745
    style C color:#FFFFFF, fill:#DC3545, stroke:#DC3545
    style D color:#FFFFFF, fill:#FFC107, stroke:#FFC107
    style F color:#FFFFFF, fill:#17A2B8, stroke:#17A2B8
    style G color:#FFFFFF, fill:#6C757D, stroke:#6C757D
    style H color:#FFFFFF, fill:#6610f2, stroke:#6610f2
    style I color:#FFFFFF, fill:#FD7E14, stroke:#FD7E14
    style J color:#FFFFFF, fill:#DC3545, stroke:#DC3545
    style K color:#FFFFFF, fill:#007BFF, stroke:#007BFF
