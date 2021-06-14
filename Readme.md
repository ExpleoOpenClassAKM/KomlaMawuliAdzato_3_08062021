Projet P3 - Formation Front-end Openclassrooms
Titre: Ohmyfood!
Ohmyfood! est une jeune startup qui voudrait s'imposer sur le marché de la restauration. L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. Finis, les temps d'attente au restaurant ! 



.mainTutorialItem {
    display: flex;
    flex-direction: column;
    justify-content: center;
    &__number {
        width: 2*$dim;
        height: 2*$dim;
        background-color: $colour-primary;
        position: absolute;
        margin-bottom: $dim;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        color: $cd-maincolour;
    }

    &__panel {
        margin-bottom: $dim;
        border: .1*$dim solid $cd-maincolour;
        border-radius: 1*$dim;
        background-color: $cd-maincolour;
        width: auto;
        font-weight: bold;   
        margin-left: $dim;  
        padding-left: 2*$dim;
        padding-top: 1.5*$dim;
        padding-bottom: 1.5*$dim;
        position: relative; 
        @include mini-mobile {
            padding-right: $dim;
        } 
        &--icon {
            margin-right: 1.5*$dim;
        }
    } 
}
