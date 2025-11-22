## Boutique Diayma2026
## 3 - Explorer l’application et signaler 2 bugs trouvés

Après avoir explorer l'application, les 2 bugs notés sont :
1. le quantité sur le stock du produit ne décrémente pas lorsque le client valide une commande.
2. La traduction de la langue Espagnol ne fonctionne pas.
## 5. Les namespaces, classes et méthodes visités avant l’affichage des produits sur l’écran d’accueil de votre navigateur, en mode "Pas à pas détaillé" sont:
namespace: P2FixAnAppDotNetCode

classe: Startup

Méthodes:Startup(IConfiguration configuration)

C’est le premier point d’entrée chargé par l’application lors de l’initialisation.

namespace: P2FixAnAppDotNetCode.Controllers

classe: ProductController

Méthode: cette étape contient le constructeur

public ProductController(IProductService productService, ILanguageService languageService)

C’est le constructeur de la classe ProductController. Visual Studio entre dans ce contrôleur pour préparer les dépendances nécessaires, notamment _productService.

namespace : P2FixAnAppDotNetCode.Components

Classe : CartSummaryViewComponent

Méthode : Le constructeur

public CartSummaryViewComponent(ICart cart), C’est le constructeur de la classe CartSummaryViewComponent.

