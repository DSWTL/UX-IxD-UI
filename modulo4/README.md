# Desarrollo de Aplicaciones Móviles para Dispositivos iOS

José Ángel González: jan.zelaznog@gmail.com

Tramitar cuenta app developer: 

https://developer.apple.com/
https://developer.apple.com/programs/

* Swift 4(https://swift.org/)
* Xcode Version 10.2.1 (10E1001)
* iOS (10.0 - 12.2)


### Xcode

Status Bar 20px
Footer 40px

Imagen de 1024 x 1024 para subir a la app store

cocoa pots


Líneas de conexión: Segue


# MVC

Vista: Storyboards and xib

xib <== NIB

xib: xml, interface, builder
NIB: Next step builder

Next Step desarrolló Objective-C
cocoa: Sistema operativo gráfico

AppDelegate: 
class AppDelegate: UIResponder, UIApplicationDelegate {

    var window: UIWindow?


    func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: [UIApplication.LaunchOptionsKey: Any]?) -> Bool {
        // Override point for customization after application launch.
        return true
    }

@IBAction: directiva del compilador


# Frameworks:
* Foundation -- NS
* UIKit - UI
* Core Graphics - CG

Image View

CGRect -- Frame: Origin(x: , y:) , Size(width:, height:)

Tamaños: 320 x 568


# Constraints

Restringir el tamaño o la posición de los objetos.@



