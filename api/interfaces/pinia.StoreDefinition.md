---
sidebar: "auto"
editLinks: false
sidebarDepth: 3
---

[Documentación de la API](../index.md) / [pinia](../modules/pinia.md) / StoreDefinition

# Interfaz: StoreDefinition<Id, S, G, A\> {#interface-storedefinition-id-s-g-a}

[pinia](../modules/pinia.md).StoreDefinition

## Tipado de los parámetros {#type-parameters}

| Nombre | Tipo |
| :------ | :------ |
| `Id` | extiende `string` = `string` |
| `S` | extiende [`StateTree`](../modules/pinia.md#statetree) = [`StateTree`](../modules/pinia.md#statetree) |
| `G` | [`_GettersTree`](../modules/pinia.md#_getterstree)<`S`\> |
| `A` | [`_ActionsTree`](../modules/pinia.md#_actionstree) |

## Invocable {#callable}

### StoreDefinition {#storedefinition}

▸ **StoreDefinition**(`pinia?`, `hot?`): [`Store`](../modules/pinia.md#store)<`Id`, `S`, `G`, `A`\>

Retorna un almacén, lo crea si es necesario.

#### Parámetros {#parameters}

| Nombre | Tipo | Descripción |
| :------ | :------ | :------ |
| `pinia?` | ``null`` \| [`Pinia`](pinia.Pinia.md) | Instancia de Pinia para obtener el almacén |
| `hot?` | [`StoreGeneric`](../modules/pinia.md#storegeneric) | hot module replacement solo para desarrollar |

#### Returns {#returns}

[`Store`](../modules/pinia.md#store)<`Id`, `S`, `G`, `A`\>

## Properties {#properties}

### $id {#id}

• **$id**: `Id`

Id de la tienda. Utilizado por los ayudantes de mapeado.
