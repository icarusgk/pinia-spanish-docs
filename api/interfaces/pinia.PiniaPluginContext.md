---
sidebar: "auto"
editLinks: false
sidebarDepth: 3
---

[Documentación de la API](../index.md) / [pinia](../modules/pinia.md) / PiniaPluginContext

# Interfaz: PiniaPluginContext<Id, S, G, A\> {#interfaz-piniaplugincontext-id-s-g-a}

[pinia](../modules/pinia.md).PiniaPluginContext

Argumento de contexto que se pasa a los plugins de Pinia.

## Tipado de los parámetros {#type-parameters}

| Nombre | Tipo |
| :------ | :------ |
| `Id` | extiende `string` = `string` |
| `S` | extiende [`StateTree`](../modules/pinia.md#statetree) = [`StateTree`](../modules/pinia.md#statetree) |
| `G` | [`_GettersTree`](../modules/pinia.md#_getterstree)<`S`\> |
| `A` | [`_ActionsTree`](../modules/pinia.md#_actionstree) |

## Properties {#properties}

### app {#app}

• **app**: `App`<`any`\>

Aplicación actual creada con `Vue.createApp()`.

___

### options {#options}

• **options**: [`DefineStoreOptionsInPlugin`](pinia.DefineStoreOptionsInPlugin.md)<`Id`, `S`, `G`, `A`\>

Opciones iniciales que definen el almacén cuando se llama a `defineStore()`.

___

### pinia {#pinia}

• **pinia**: [`Pinia`](pinia.Pinia.md)

instancia pinia.

___

### store {#store}

• **store**: [`Store`](../modules/pinia.md#store)<`Id`, `S`, `G`, `A`\>

Tienda actual que se está extendiendo.
