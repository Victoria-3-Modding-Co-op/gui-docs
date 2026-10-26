# Data-binding types: V

Back to the [index](README.md).

## VariableEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessScopeEditor` |  | `ScopeObjectEditor` |  |
| `AccessSelf` |  |  |  |
| `Delete` |  | `void` |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |
| `SetName` |  | `void` |  |

## VariableInspectorEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessVariable` |  | `VariableInspectorVariable` |  |
| `AccessSelf` |  |  |  |
| `Delete` |  | `void` |  |
| `Self` |  |  |  |

## VariableInspectorPlugin

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSetupVariable` |  | `VariableInspectorVariable` |  |
| `AccessSelf` |  |  |  |
| `AccessVariables` |  |  |  |
| `AddVariable` |  | `void` |  |
| `GetNumVariables` |  | `int32` |  |
| `Self` |  |  |  |

## VariableInspectorVariable

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessScopeEditor` |  | `ScopeObjectEditor` |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetRemainingTicks` |  | `int32` |  |
| `Self` |  |  |  |
| `SetName` |  | `void` |  |
| `SetRemainingTicks` |  | `void` |  |

## VariableList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessEntries` |  |  |  |
| `AccessSelf` |  |  |  |
| `Delete` |  | `void` |  |
| `GetName` |  | `CString` |  |
| `GetSize` |  | `int32` |  |
| `Self` |  |  |  |

## VariableListEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessScopeEditor` |  | `ScopeObjectEditor` |  |
| `AccessSelf` |  |  |  |
| `Delete` |  | `void` |  |
| `GetTicksRemaining` |  | `int32` |  |
| `Self` |  |  |  |
| `SetTicksRemaining` |  | `void` |  |

## VariableListInspectorPlugin

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessListStore` |  | `VariableListStore` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## VariableListStore

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessNewEntryEditor` |  | `ScopeObjectEditor` |  |
| `AccessSelf` |  |  |  |
| `AccessVariableLists` |  |  |  |
| `AddNewEntry` |  | `void` |  |
| `GetNewVariableListName` |  | `CString` |  |
| `GetNumVariableLists` |  | `int32` |  |
| `GetVariableTicksRemaining` |  | `int32` |  |
| `Self` |  |  |  |
| `SetNewVariableListName` |  | `void` |  |
| `SetVariableTicksRemaining` |  | `void` |  |

## VariableStore

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessNewEntryEditor` |  | `ScopeObjectEditor` |  |
| `AccessSelf` |  |  |  |
| `AccessVariables` |  |  |  |
| `AddNewEntry` |  | `void` |  |
| `GetNewVariableName` |  | `CString` |  |
| `GetNumVariables` |  | `int32` |  |
| `Self` |  |  |  |
| `SetNewVariableName` |  | `void` |  |

## VariableSystem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Clear` | `Arg0` | `void` |  |
| `ClearIf` | `Arg0, Arg1` | `void` |  |
| `ClearMultiple` | `Arg0, Arg1` | `void` |  |
| `Exists` | `Arg0` | `bool` |  |
| `Get` | `Arg0` | `CString` |  |
| `HasValue` | `Arg0, Arg1` | `bool` |  |
| `Self` |  |  |  |
| `Set` | `Arg0, Arg1` | `void` |  |
| `SetIf` | `Arg0, Arg1, Arg2` | `void` |  |
| `SetOrToggle` | `Arg0, Arg1` | `void` |  |
| `Toggle` | `Arg0` | `bool` |  |

## VfsMountPathBrowser

Gui Data Profiler Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstSelectedNode` |  | `VfsMountPathBrowserEntryNode` |  |
| `AccessSelf` |  |  |  |
| `GetFilter` |  | `CString` |  |
| `GetNodeTree` |  |  |  |
| `GetNumSelectedNodes` |  | `int32` |  |
| `HasDirectFilterMatch` | `Arg0` | `bool` |  |
| `IsNodeExpanded` | `Arg0` | `bool` |  |
| `IsNodeSelected` | `Arg0` | `bool` |  |
| `IsRefreshingDirectories` |  | `bool` |  |
| `OnCancel` |  | `void` |  |
| `OnFilterEdit` |  | `void` |  |
| `OnSelect` |  | `void` |  |
| `RefreshAllDirectories` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleNodeExpanded` | `Arg0` | `void` |  |
| `ToggleNodeSelected` | `Arg0` | `void` |  |

## VfsMountPathBrowserEntryNode

Gui Data Profiler tree entry node

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBranchDepth` | `Arg0, Arg1` | `CVector2f` |  |
| `GetFullPath` |  |  |  |
| `GetName` |  |  |  |
| `HasChildren` |  | `bool` |  |
| `Self` |  |  |  |

## ViewerEntity

Entity Editor - Entity

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `State` |  | `ViewerEntityState` |  |
| `AccessSelf` |  |  |  |
| `CurrentFrame` |  | `int32` |  |
| `CurrentTime` |  | `double` |  |
| `EntityLods` |  |  |  |
| `HasStates` |  | `bool` |  |
| `HasUnsavedChanges` |  | `bool` |  |
| `IsLooping` |  | `bool` |  |
| `IsPlaying` |  | `bool` |  |
| `Name` |  |  |  |
| `NumJoints` |  | `int32` |  |
| `PauseAnimation` |  | `void` |  |
| `RollForward` |  | `void` |  |
| `Rollback` |  | `void` |  |
| `Scale` |  | `float` |  |
| `Self` |  |  |  |
| `SetCurrentFrameText` | `Arg0` | `void` |  |
| `SetCurrentTimeText` | `Arg0` | `void` |  |
| `State` |  |  |  |
| `StepBackwards` |  | `void` |  |
| `StepForward` |  | `void` |  |
| `ToggleLooping` |  | `void` |  |
| `TogglePausePlay` |  | `void` |  |

## ViewerEntityLodInfo

Entity Editor - Entity LodInfo

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Lod` |  | `int32` |  |
| `NumTriangles` |  | `int32` |  |
| `NumVertices` |  | `int32` |  |
| `Self` |  |  |  |

## ViewerEntityState

Entity Editor - Entity State

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AnimationLength` |  | `float` |  |
| `HasAnimation` |  | `bool` |  |
| `KeyframeLayers` |  |  |  |
| `Name` |  |  |  |
| `NumFrames` |  | `int32` |  |
| `Self` |  |  |  |

## void

Unspecified type / empty type.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
