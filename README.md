# VIPER module template
It creates
- ViewController as View with *.xib
- Presenter
- Interactor
- Router
  - In this template router is also a configurator/builder
- Contract file containing all protocols

# Шаблон модуля с VIPER архитектурой
Создает
- View в виде ViewController и *.xib для него
- Presenter
- Interactor
- Router. В данном шаблоне также отвечает за создание модуля
- Файл Contract, содержащий описание протоколов взаимодействия компонентов модуля

# HOW TO
1. Install [generamba](https://github.com/strongself/Generamba) with `gem install generamba`
2. Add this template like `- {name: viper_template, git: 'https://github.com/Vetas-R/viper_template'}`
3. Run `generamba template install`

Now you can use `generamba gen [module_name] viper_template` to generate new module with generamba and this template.
