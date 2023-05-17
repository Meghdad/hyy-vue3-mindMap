# A web mind map based on Vue3.2 + ElementPlus

## Project Preview
### Project Address：[Mind Mapping](https://huangyuanyin.gitee.io/hyy-vue3-mindmap/#/)
![image](https://user-images.githubusercontent.com/42410679/219315595-5b948055-ebe9-45c0-a2ab-e640d4a09feb.png)
![image](https://user-images.githubusercontent.com/42410679/208390826-60ded4ce-ad48-46da-ab84-c66c3ef29885.png)
![image](https://user-images.githubusercontent.com/42410679/208390888-401d8c91-f76b-4c3b-a095-24daccae8404.png)



## Characteristic

- [x] Plug-in architecture, in addition to the core functions, other functions are provided as plug-ins, which can be used on demand and reduce the overall size
- [x] Support logical structure chart, mind map, organization chart, directory organization chart four structures
- [x] Multiple built-in themes allow highly customizable styles
- [x] Support shortcut keys
- [x] Node content supports pictures, icons, hyperlinks, notes, labels, and summaries
- [x] Support forward and backward
- [x] Support dragging and zooming
- [x] Support right click and hold for multiple selection
- [x] Support node free dragging and dragging adjustment
- [x] Supports multiple node shapes
- [x] Support exporting to `json`, `png`, `svg`, `pdf`, support importing from `json`, `xmind`
- [x] Support small map
- [x] Support small map, support watermark

## Tool library introduction
1.`simple-mind-map`
Mind mapping tool library, framework-independent, `Vue`, `React` and other frameworks or no frameworks can be used.

2.Using the `simple-mind-map` tool library, an online mind map based on `vue3.2` and `ElementPlus`. characteristic:

- [x] Toolbar, supports inserting nodes, deleting nodes; editing node pictures, icons, hyperlinks, notes, labels, and summaries

- [x] Sidebar, basic style setting panel, node style setting panel, outline panel, theme selection panel, structure selection panel

- [x] Import and export function; the data is saved in the local storage of the browser by default, and it also supports the direct creation, opening and editing of local files on the computer

- [x] The right-click menu supports operations such as expanding, collapsing, and arranging the layout

- [x] The bottom bar supports the number of nodes and word count; supports switching between editing and read-only modes; supports zooming in and out; supports full-screen switching; supports small maps

## to develop

### local development
```bash
git clone https://github.com/huangyuanyin/hyy-vue3-mindMap.git
npm i
npm run serve
```

## late plan
- [ ] Migrate project from vue-cli to vite
- [ ] Change the project from JS to TS writing

# Special Note

This project is relatively rough and has not been fully tested. The function is not perfect yet, and there are some problems in performance. It is only for learning and reference, and please do not use it for actual projects.

This project is based on refactoring the vue3 + elementplus version on https://github.com/wanglin2/mind-map.

The themes and icons built into the project come from:

[Baidu brain map](https://naotu.baidu.com/)

[Zhixi mind map](https://www.zhixi.com/)
