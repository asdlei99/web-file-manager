# fc-file-manager

![文件截图](https://s2.ax1x.com/2020/03/02/32cUbR.md.png)

## Feature

- 能提供列表、网格等多种视图。
- 提供拖拽放入、排序等功能。
- 提供扩展接口：视图渲染回调、右击工具菜单渲染回调。

## Usage

```tsx
import { dummyFileSystem } from './dummyFileSystem';

export default function Simple() {
  return <UfFileManager fileMap={dummyFileSystem} />;
}
```

# About

## Roadmap

- [ ] 允许传入自定义的渲染函数
- [ ] 使用 react-beautiful-dnd 添加拖拽功能

## Motivation & Credits

### File Manager

- [el-file #Project#](https://github.com/mflorence99/el-file): The Elf file manager is the latest. My motivation throughout has partly been that few Linux tools have the kind of rich UI you can build today with tools like Angular and Material Design.

- [electron-quasar-file-explorer #Project#](https://github.com/hawkeye64/electron-quasar-file-explorer): A Simple File Explorer using Vue/Quasar/Electron

- [JumpFm #Project#](https://jumpfm.org/#Builtin%20Super-Powers): A file manager that lets you jump.

- [filemanager #Project#](https://github.com/OpusCapita/filemanager): React based FileManager for browser ( + FS REST API for Node.js and Express)

- [file-system-react #Project#](https://github.com/imshubhamsingh/file-system-react): File System UI in Web using react.

### File Preview

- [wopihost #Project#](https://github.com/ethendev/wopihost): 基于 wopi 协议开发的 WopiHost , 支持 word, excel，ppt, pdf(仅支持预览)等文档的预览和编辑。
