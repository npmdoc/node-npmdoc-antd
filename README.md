# api documentation for  [antd (v2.9.0)](http://ant.design/)  [![npm package](https://img.shields.io/npm/v/npmdoc-antd.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-antd) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-antd.svg)](https://travis-ci.org/npmdoc/node-npmdoc-antd)
#### An enterprise-class UI design language and React-based implementation

[![NPM](https://nodei.co/npm/antd.png?downloads=true)](https://www.npmjs.com/package/antd)

[![apidoc](https://npmdoc.github.io/node-npmdoc-antd/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-antd_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-antd/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-antd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-antd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/ant-design/ant-design/issues"
    },
    "contributors": [
        {
            "name": "ant"
        }
    ],
    "dependencies": {
        "array-tree-filter": "~1.0.0",
        "babel-runtime": "6.x",
        "classnames": "~2.2.0",
        "css-animation": "^1.2.5",
        "dom-closest": "^0.2.0",
        "lodash.debounce": "^4.0.8",
        "moment": "~2.18.0",
        "object-assign": "~4.1.0",
        "omit.js": "^0.1.0",
        "rc-animate": "~2.3.0",
        "rc-calendar": "~7.8.0",
        "rc-cascader": "~0.11.0",
        "rc-checkbox": "~1.5.0",
        "rc-collapse": "~1.6.4",
        "rc-dialog": "~6.5.0",
        "rc-dropdown": "~1.4.8",
        "rc-editor-mention": "~0.5.2",
        "rc-form": "~1.3.0",
        "rc-input-number": "~3.4.4",
        "rc-menu": "~5.0.9",
        "rc-notification": "~1.4.0",
        "rc-pagination": "~1.8.0",
        "rc-progress": "~2.1.0",
        "rc-radio": "~2.0.0",
        "rc-rate": "~2.1.0",
        "rc-select": "~6.8.0",
        "rc-slider": "~6.3.0",
        "rc-steps": "~2.4.0",
        "rc-switch": "~1.4.2",
        "rc-table": "~5.2.13",
        "rc-tabs": "~7.3.0",
        "rc-time-picker": "~2.3.3",
        "rc-tooltip": "~3.4.2",
        "rc-tree": "~1.4.0",
        "rc-tree-select": "~1.9.0",
        "rc-upload": "~2.3.0",
        "rc-util": "^4.0.1",
        "react-lazy-load": "^3.0.10",
        "react-slick": "~0.14.2",
        "shallowequal": "^0.2.2",
        "warning": "~3.0.0"
    },
    "description": "An enterprise-class UI design language and React-based implementation",
    "devDependencies": {
        "@types/react": "^15.0.8",
        "@types/react-dom": "~0.14.18",
        "antd-demo-jest": "^1.0.5",
        "antd-tools": "~0.19.1",
        "babel-cli": "^6.18.0",
        "babel-eslint": "^7.1.0",
        "babel-jest": "^19.0.0",
        "babel-plugin-import": "^1.0.0",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "bezier-easing": "^2.0.3",
        "bisheng": "^0.23.0",
        "bisheng-plugin-antd": "^0.13.2",
        "bisheng-plugin-description": "^0.1.1",
        "bisheng-plugin-react": "^0.5.0",
        "bisheng-plugin-toc": "^0.4.0",
        "color-standalone": "^0.11.6",
        "cross-env": "^3.1.4",
        "css-split-webpack-plugin": "^0.2.3",
        "dekko": "^0.2.0",
        "dora-plugin-upload": "^0.3.1",
        "enquire.js": "^2.1.1",
        "enzyme": "^2.6.0",
        "enzyme-to-json": "^1.3.0",
        "eslint": "^3.0.1",
        "eslint-config-airbnb": "latest",
        "eslint-plugin-babel": "^4.0.0",
        "eslint-plugin-import": "^2.1.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-react": "^6.10.3",
        "eslint-tinker": "^0.4.0",
        "fetch-jsonp": "^1.0.3",
        "glob": "^7.1.1",
        "jest": "^19.0.2",
        "jsonml.js": "^0.1.0",
        "lint-staged": "^3.3.1",
        "mockdate": "^2.0.1",
        "moment-timezone": "^0.5.5",
        "pre-commit": "^1.2.2",
        "querystring": "^0.2.0",
        "rc-queue-anim": "^0.13.2",
        "rc-scroll-anim": "^1.0.3",
        "rc-tween-one": "^1.1.2",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-color-standalone": "^2.4.2-1",
        "react-copy-to-clipboard": "^4.0.1",
        "react-document-title": "^2.0.1",
        "react-dom": "^15.0.0",
        "react-github-button": "^0.1.1",
        "react-intl": "^2.0.1",
        "react-stateless-wrapper": "^1.0.2",
        "react-sublime-video": "^0.2.0",
        "reqwest": "^2.0.5",
        "rimraf": "^2.5.4",
        "stylelint": "^7.8.0",
        "stylelint-config-standard": "^16.0.0",
        "typescript": "~2.2.1",
        "typescript-babel-jest": "^1.0.2",
        "values.js": "^1.0.3",
        "xhr2": "^0.1.3"
    },
    "directories": {},
    "dist": {
        "shasum": "da21db9bbb8a9ec3444a6440462bb8e4e37ad82c",
        "tarball": "https://registry.npmjs.org/antd/-/antd-2.9.0.tgz"
    },
    "files": [
        "dist",
        "lib"
    ],
    "gitHead": "6864fea0cb2ab55c5b9f6d280bc60385fc51580c",
    "homepage": "http://ant.design/",
    "jest": {
        "setupFiles": [
            "./tests/setup.js"
        ],
        "moduleFileExtensions": [
            "ts",
            "tsx",
            "js",
            "jsx",
            "json",
            "md"
        ],
        "modulePathIgnorePatterns": [
            "/_site/"
        ],
        "testPathIgnorePatterns": [
            "dekko",
            "/node_modules/",
            "node"
        ],
        "transform": {
            "\\.tsx?$": "./node_modules/typescript-babel-jest",
            "\\.js$": "./node_modules/babel-jest",
            "\\.md$": "./node_modules/antd-demo-jest"
        },
        "testRegex": ".*\\.test\\.js$",
        "collectCoverageFrom": [
            "components/**/*.{ts,tsx}",
            "!components/*/style/index.tsx"
        ],
        "transformIgnorePatterns": [
            "/node_modules/",
            "/dist/antd.js"
        ]
    },
    "keywords": [
        "ant",
        "design",
        "react",
        "react-component",
        "component",
        "components",
        "ui",
        "framework",
        "frontend"
    ],
    "license": "MIT",
    "lint-staged": {
        "components/**/*.tsx": [
            "lint-staged:ts"
        ],
        "{tests,site,scripts,components}/**/*.{js,jsx}": [
            "lint-staged:es"
        ],
        "{site,components}/**/*.less": "stylelint --syntax less",
        "components/*/demo/*.md": [
            "lint-staged:demo"
        ]
    },
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "benjycui",
            "email": "benjytrys@gmail.com"
        }
    ],
    "name": "antd",
    "optionalDependencies": {},
    "pre-commit": [
        "lint-staged"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ant-design/ant-design.git"
    },
    "scripts": {
        "authors": "git log --format='%aN <%aE>' | sort -u | grep -v 'users.noreply.github.com' | grep -v 'gitter.im' | grep -v '.local>' | grep -v 'alibaba-inc.com' | grep -v 'alipay.com' | grep -v 'taobao.com' > AUTHORS.txt",
        "compile": "antd-tools run compile",
        "deploy": "antd-tools run clean && npm run site && bisheng gh-pages --push-only",
        "dist": "antd-tools run dist",
        "lint": "npm run lint:ts && npm run lint:es && npm run lint:demo && npm run lint:style",
        "lint-fix": "npm run lint-fix:code && npm run lint-fix:demo",
        "lint-fix:code": "eslint --fix tests site scripts components ./.eslintrc.js ./webpack.config.js --ext '.js,.jsx'",
        "lint-fix:demo": "eslint-tinker ./components/*/demo/*.md",
        "lint-fix:ts": "npm run tsc && antd-tools run ts-lint-fix",
        "lint-staged": "lint-staged",
        "lint-staged:demo": "cross-env RUN_ENV=DEMO eslint --ext '.md'",
        "lint-staged:es": "eslint ./.eslintrc.js ./webpack.config.js",
        "lint-staged:ts": "tsc && node node_modules/tslint/bin/tslint -c node_modules/antd-tools/lib/tslint.json",
        "lint:demo": "cross-env RUN_ENV=DEMO eslint components/*/demo/*.md --ext '.md'",
        "lint:es": "eslint tests site scripts components ./.eslintrc.js ./webpack.config.js --ext '.js,.jsx'",
        "lint:style": "stylelint \"{site,components}/**/*.less\" --syntax less",
        "lint:ts": "npm run tsc && antd-tools run ts-lint",
        "pre-publish": "npm run test-all && node ./scripts/prepub",
        "prepublish": "antd-tools run guard",
        "pub": "antd-tools run pub",
        "site": "bisheng build --ssr -c ./site/bisheng.config.js",
        "start": "bisheng start -c ./site/bisheng.config.js --no-livereload",
        "test": "jest",
        "test-all": "./scripts/test-all.sh",
        "tsc": "tsc"
    },
    "title": "Ant Design",
    "typings": "lib/index.d.ts",
    "version": "2.9.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module antd](#apidoc.module.antd)
1.  [function <span class="apidocSignatureSpan">antd.</span>Affix (props)](#apidoc.element.antd.Affix)
1.  [function <span class="apidocSignatureSpan">antd.</span>Alert (props)](#apidoc.element.antd.Alert)
1.  [function <span class="apidocSignatureSpan">antd.</span>Anchor (props)](#apidoc.element.antd.Anchor)
1.  [function <span class="apidocSignatureSpan">antd.</span>Anchor.Link ()](#apidoc.element.antd.Anchor.Link)
1.  [function <span class="apidocSignatureSpan">antd.</span>AutoComplete ()](#apidoc.element.antd.AutoComplete)
1.  [function <span class="apidocSignatureSpan">antd.</span>BackTop (props)](#apidoc.element.antd.BackTop)
1.  [function <span class="apidocSignatureSpan">antd.</span>Badge ()](#apidoc.element.antd.Badge)
1.  [function <span class="apidocSignatureSpan">antd.</span>Breadcrumb ()](#apidoc.element.antd.Breadcrumb)
1.  [function <span class="apidocSignatureSpan">antd.</span>Breadcrumb.Item ()](#apidoc.element.antd.Breadcrumb.Item)
1.  [function <span class="apidocSignatureSpan">antd.</span>Button (props)](#apidoc.element.antd.Button)
1.  [function <span class="apidocSignatureSpan">antd.</span>Calendar (props, context)](#apidoc.element.antd.Calendar)
1.  [function <span class="apidocSignatureSpan">antd.</span>Card (props)](#apidoc.element.antd.Card)
1.  [function <span class="apidocSignatureSpan">antd.</span>Carousel ()](#apidoc.element.antd.Carousel)
1.  [function <span class="apidocSignatureSpan">antd.</span>Cascader (props)](#apidoc.element.antd.Cascader)
1.  [function <span class="apidocSignatureSpan">antd.</span>Checkbox ()](#apidoc.element.antd.Checkbox)
1.  [function <span class="apidocSignatureSpan">antd.</span>Checkbox.Group (props)](#apidoc.element.antd.Checkbox.Group)
1.  [function <span class="apidocSignatureSpan">antd.</span>Col ()](#apidoc.element.antd.Col)
1.  [function <span class="apidocSignatureSpan">antd.</span>Collapse ()](#apidoc.element.antd.Collapse)
1.  [function <span class="apidocSignatureSpan">antd.</span>Collapse.Panel (props, context, updater)](#apidoc.element.antd.Collapse.Panel)
1.  [function <span class="apidocSignatureSpan">antd.</span>DatePicker (props, context, updater)](#apidoc.element.antd.DatePicker)
1.  [function <span class="apidocSignatureSpan">antd.</span>DatePicker.Calendar ()](#apidoc.element.antd.DatePicker.Calendar)
1.  [function <span class="apidocSignatureSpan">antd.</span>DatePicker.MonthPicker (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker)
1.  [function <span class="apidocSignatureSpan">antd.</span>DatePicker.RangePicker (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker)
1.  [function <span class="apidocSignatureSpan">antd.</span>Dropdown ()](#apidoc.element.antd.Dropdown)
1.  [function <span class="apidocSignatureSpan">antd.</span>Dropdown.Button ()](#apidoc.element.antd.Dropdown.Button)
1.  [function <span class="apidocSignatureSpan">antd.</span>Form (props)](#apidoc.element.antd.Form)
1.  [function <span class="apidocSignatureSpan">antd.</span>Form.Item ()](#apidoc.element.antd.Form.Item)
1.  [function <span class="apidocSignatureSpan">antd.</span>Icon (props)](#apidoc.element.antd.Icon)
1.  [function <span class="apidocSignatureSpan">antd.</span>Input ()](#apidoc.element.antd.Input)
1.  [function <span class="apidocSignatureSpan">antd.</span>Input.Search ()](#apidoc.element.antd.Input.Search)
1.  [function <span class="apidocSignatureSpan">antd.</span>InputNumber ()](#apidoc.element.antd.InputNumber)
1.  [function <span class="apidocSignatureSpan">antd.</span>Layout ()](#apidoc.element.antd.Layout)
1.  [function <span class="apidocSignatureSpan">antd.</span>Layout.Content ()](#apidoc.element.antd.Layout.Content)
1.  [function <span class="apidocSignatureSpan">antd.</span>Layout.Footer ()](#apidoc.element.antd.Layout.Footer)
1.  [function <span class="apidocSignatureSpan">antd.</span>Layout.Header ()](#apidoc.element.antd.Layout.Header)
1.  [function <span class="apidocSignatureSpan">antd.</span>Layout.Sider (props)](#apidoc.element.antd.Layout.Sider)
1.  [function <span class="apidocSignatureSpan">antd.</span>LocaleProvider ()](#apidoc.element.antd.LocaleProvider)
1.  [function <span class="apidocSignatureSpan">antd.</span>Mention {{signature}}](#apidoc.element.antd.Mention)
1.  [function <span class="apidocSignatureSpan">antd.</span>Mention.Nav ()](#apidoc.element.antd.Mention.Nav)
1.  [function <span class="apidocSignatureSpan">antd.</span>Menu (props)](#apidoc.element.antd.Menu)
1.  [function <span class="apidocSignatureSpan">antd.</span>Menu.Divider (props, context, updater)](#apidoc.element.antd.Menu.Divider)
1.  [function <span class="apidocSignatureSpan">antd.</span>Menu.Item (props, context, updater)](#apidoc.element.antd.Menu.Item)
1.  [function <span class="apidocSignatureSpan">antd.</span>Menu.ItemGroup (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup)
1.  [function <span class="apidocSignatureSpan">antd.</span>Menu.SubMenu (props, context, updater)](#apidoc.element.antd.Menu.SubMenu)
1.  [function <span class="apidocSignatureSpan">antd.</span>Modal ()](#apidoc.element.antd.Modal)
1.  [function <span class="apidocSignatureSpan">antd.</span>Pagination ()](#apidoc.element.antd.Pagination)
1.  [function <span class="apidocSignatureSpan">antd.</span>Popconfirm ()](#apidoc.element.antd.Popconfirm)
1.  [function <span class="apidocSignatureSpan">antd.</span>Popover ()](#apidoc.element.antd.Popover)
1.  [function <span class="apidocSignatureSpan">antd.</span>Progress ()](#apidoc.element.antd.Progress)
1.  [function <span class="apidocSignatureSpan">antd.</span>Radio ()](#apidoc.element.antd.Radio)
1.  [function <span class="apidocSignatureSpan">antd.</span>Radio.Button ()](#apidoc.element.antd.Radio.Button)
1.  [function <span class="apidocSignatureSpan">antd.</span>Radio.Group (props)](#apidoc.element.antd.Radio.Group)
1.  [function <span class="apidocSignatureSpan">antd.</span>Rate ()](#apidoc.element.antd.Rate)
1.  [function <span class="apidocSignatureSpan">antd.</span>Row ()](#apidoc.element.antd.Row)
1.  [function <span class="apidocSignatureSpan">antd.</span>Select ()](#apidoc.element.antd.Select)
1.  [function <span class="apidocSignatureSpan">antd.</span>Slider (props)](#apidoc.element.antd.Slider)
1.  [function <span class="apidocSignatureSpan">antd.</span>Spin (props)](#apidoc.element.antd.Spin)
1.  [function <span class="apidocSignatureSpan">antd.</span>Steps ()](#apidoc.element.antd.Steps)
1.  [function <span class="apidocSignatureSpan">antd.</span>Steps.Step ()](#apidoc.element.antd.Steps.Step)
1.  [function <span class="apidocSignatureSpan">antd.</span>Switch ()](#apidoc.element.antd.Switch)
1.  [function <span class="apidocSignatureSpan">antd.</span>Table (props)](#apidoc.element.antd.Table)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tabs ()](#apidoc.element.antd.Tabs)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tabs.TabPane (props, context, updater)](#apidoc.element.antd.Tabs.TabPane)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tag (props)](#apidoc.element.antd.Tag)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tag.CheckableTag ()](#apidoc.element.antd.Tag.CheckableTag)
1.  [function <span class="apidocSignatureSpan">antd.</span>TimePicker ()](#apidoc.element.antd.TimePicker)
1.  [function <span class="apidocSignatureSpan">antd.</span>Timeline ()](#apidoc.element.antd.Timeline)
1.  [function <span class="apidocSignatureSpan">antd.</span>Timeline.Item ()](#apidoc.element.antd.Timeline.Item)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tooltip (props)](#apidoc.element.antd.Tooltip)
1.  [function <span class="apidocSignatureSpan">antd.</span>Transfer ()](#apidoc.element.antd.Transfer)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tree ()](#apidoc.element.antd.Tree)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tree.TreeNode (props)](#apidoc.element.antd.Tree.TreeNode)
1.  [function <span class="apidocSignatureSpan">antd.</span>TreeSelect ()](#apidoc.element.antd.TreeSelect)
1.  [function <span class="apidocSignatureSpan">antd.</span>Upload (props)](#apidoc.element.antd.Upload)
1.  [function <span class="apidocSignatureSpan">antd.</span>Upload.Dragger ()](#apidoc.element.antd.Upload.Dragger)
1.  object <span class="apidocSignatureSpan">antd.</span>Affix.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Affix.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Alert.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Anchor.Link.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Anchor.childContextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Anchor.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>AutoComplete.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>BackTop.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Badge.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Badge.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Breadcrumb.Item.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Breadcrumb.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Breadcrumb.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Button.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Button.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Calendar.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Calendar.defaultProps
1.  object <span class="apidocSignatureSpan">antd.</span>Calendar.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Calendar.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Carousel.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Cascader.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Checkbox.Group.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Checkbox.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Col.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Col.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Collapse.Panel.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Collapse.Panel.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Collapse.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.Calendar.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.MonthPicker.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.MonthPicker.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.RangePicker.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.RangePicker.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.defaultProps
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>DatePicker.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Dropdown.Button.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Dropdown.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Form.Item.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Form.childContextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Form.defaultProps
1.  object <span class="apidocSignatureSpan">antd.</span>Form.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Form.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Input.Search.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Input.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Input.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>InputNumber.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Layout.Content.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Layout.Footer.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Layout.Header.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Layout.Sider.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Layout.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>LocaleProvider.childContextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>LocaleProvider.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>LocaleProvider.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Mention.Nav.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Mention.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.Divider.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.Divider.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.Item.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.Item.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.ItemGroup.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.ItemGroup.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.SubMenu.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.SubMenu.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Menu.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Modal.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Modal.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Modal.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Pagination.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Pagination.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Popconfirm.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Popconfirm.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Popover.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Progress.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Progress.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Radio.Button.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Radio.Group.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Radio.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Radio.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Rate.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Rate.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Row.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Row.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Select.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Select.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Slider.defaultProps
1.  object <span class="apidocSignatureSpan">antd.</span>Slider.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Spin.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Spin.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Steps.Step.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Steps.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Steps.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Switch.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Switch.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Table.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Table.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Table.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tabs.TabPane.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tabs.TabPane.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.</span>Tabs.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tag.CheckableTag.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tag.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>TimePicker.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>TimePicker.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Timeline.Item.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Timeline.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tooltip.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Transfer.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Transfer.defaultProps
1.  object <span class="apidocSignatureSpan">antd.</span>Transfer.propTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Transfer.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tree.TreeNode.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Tree.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>TreeSelect.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>TreeSelect.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Upload.Dragger.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>Upload.contextTypes
1.  object <span class="apidocSignatureSpan">antd.</span>Upload.defaultProps
1.  object <span class="apidocSignatureSpan">antd.</span>Upload.prototype
1.  object <span class="apidocSignatureSpan">antd.</span>message
1.  object <span class="apidocSignatureSpan">antd.</span>notification
1.  string <span class="apidocSignatureSpan">antd.</span>version

#### [module antd.Affix](#apidoc.module.antd.Affix)
1.  [function <span class="apidocSignatureSpan">antd.</span>Affix (props)](#apidoc.element.antd.Affix.Affix)
1.  object <span class="apidocSignatureSpan">antd.Affix.</span>propTypes

#### [module antd.Affix.propTypes](#apidoc.module.antd.Affix.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Affix.propTypes.</span>offsetBottom ()](#apidoc.element.antd.Affix.propTypes.offsetBottom)
1.  [function <span class="apidocSignatureSpan">antd.Affix.propTypes.</span>offsetTop ()](#apidoc.element.antd.Affix.propTypes.offsetTop)
1.  [function <span class="apidocSignatureSpan">antd.Affix.propTypes.</span>target ()](#apidoc.element.antd.Affix.propTypes.target)

#### [module antd.Affix.prototype](#apidoc.module.antd.Affix.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>clearScrollEventListeners ()](#apidoc.element.antd.Affix.prototype.clearScrollEventListeners)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>componentDidMount ()](#apidoc.element.antd.Affix.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Affix.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Affix.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>render ()](#apidoc.element.antd.Affix.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>setAffixStyle (e, affixStyle)](#apidoc.element.antd.Affix.prototype.setAffixStyle)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>setPlaceholderStyle (placeholderStyle)](#apidoc.element.antd.Affix.prototype.setPlaceholderStyle)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>setTargetEventListeners (getTarget)](#apidoc.element.antd.Affix.prototype.setTargetEventListeners)
1.  [function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>updatePosition (e)](#apidoc.element.antd.Affix.prototype.updatePosition)

#### [module antd.Alert](#apidoc.module.antd.Alert)
1.  [function <span class="apidocSignatureSpan">antd.</span>Alert (props)](#apidoc.element.antd.Alert.Alert)
1.  object <span class="apidocSignatureSpan">antd.Alert.</span>defaultProps

#### [module antd.Alert.prototype](#apidoc.module.antd.Alert.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Alert.prototype.</span>render ()](#apidoc.element.antd.Alert.prototype.render)

#### [module antd.Anchor](#apidoc.module.antd.Anchor)
1.  [function <span class="apidocSignatureSpan">antd.</span>Anchor (props)](#apidoc.element.antd.Anchor.Anchor)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.</span>Link ()](#apidoc.element.antd.Anchor.Link)
1.  object <span class="apidocSignatureSpan">antd.Anchor.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Anchor.</span>defaultProps

#### [module antd.Anchor.Link](#apidoc.module.antd.Anchor.Link)
1.  boolean <span class="apidocSignatureSpan">antd.Anchor.Link.</span>__ANT_ANCHOR_LINK
1.  [function <span class="apidocSignatureSpan">antd.Anchor.</span>Link ()](#apidoc.element.antd.Anchor.Link.Link)
1.  object <span class="apidocSignatureSpan">antd.Anchor.Link.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Anchor.Link.</span>defaultProps

#### [module antd.Anchor.Link.prototype](#apidoc.module.antd.Anchor.Link.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>componentDidMount ()](#apidoc.element.antd.Anchor.Link.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.Anchor.Link.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>render ()](#apidoc.element.antd.Anchor.Link.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>setActiveAnchor ()](#apidoc.element.antd.Anchor.Link.prototype.setActiveAnchor)

#### [module antd.Anchor.childContextTypes](#apidoc.module.antd.Anchor.childContextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.childContextTypes.</span>anchorHelper ()](#apidoc.element.antd.Anchor.childContextTypes.anchorHelper)

#### [module antd.Anchor.prototype](#apidoc.module.antd.Anchor.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>componentDidMount ()](#apidoc.element.antd.Anchor.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.Anchor.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Anchor.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>getChildContext ()](#apidoc.element.antd.Anchor.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>render ()](#apidoc.element.antd.Anchor.prototype.render)

#### [module antd.AutoComplete](#apidoc.module.antd.AutoComplete)
1.  [function <span class="apidocSignatureSpan">antd.</span>AutoComplete ()](#apidoc.element.antd.AutoComplete.AutoComplete)
1.  [function <span class="apidocSignatureSpan">antd.AutoComplete.</span>OptGroup ()](#apidoc.element.antd.AutoComplete.OptGroup)
1.  [function <span class="apidocSignatureSpan">antd.AutoComplete.</span>Option ()](#apidoc.element.antd.AutoComplete.Option)
1.  object <span class="apidocSignatureSpan">antd.AutoComplete.</span>defaultProps

#### [module antd.AutoComplete.prototype](#apidoc.module.antd.AutoComplete.prototype)
1.  [function <span class="apidocSignatureSpan">antd.AutoComplete.prototype.</span>render ()](#apidoc.element.antd.AutoComplete.prototype.render)

#### [module antd.BackTop](#apidoc.module.antd.BackTop)
1.  [function <span class="apidocSignatureSpan">antd.</span>BackTop (props)](#apidoc.element.antd.BackTop.BackTop)
1.  object <span class="apidocSignatureSpan">antd.BackTop.</span>defaultProps

#### [module antd.BackTop.prototype](#apidoc.module.antd.BackTop.prototype)
1.  [function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>componentDidMount ()](#apidoc.element.antd.BackTop.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.BackTop.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>render ()](#apidoc.element.antd.BackTop.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>setScrollTop (value)](#apidoc.element.antd.BackTop.prototype.setScrollTop)

#### [module antd.Badge](#apidoc.module.antd.Badge)
1.  [function <span class="apidocSignatureSpan">antd.</span>Badge ()](#apidoc.element.antd.Badge.Badge)
1.  object <span class="apidocSignatureSpan">antd.Badge.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Badge.</span>propTypes

#### [module antd.Badge.propTypes](#apidoc.module.antd.Badge.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>count ()](#apidoc.element.antd.Badge.propTypes.count)
1.  [function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>dot ()](#apidoc.element.antd.Badge.propTypes.dot)
1.  [function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>overflowCount ()](#apidoc.element.antd.Badge.propTypes.overflowCount)
1.  [function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>showZero ()](#apidoc.element.antd.Badge.propTypes.showZero)

#### [module antd.Badge.prototype](#apidoc.module.antd.Badge.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Badge.prototype.</span>render ()](#apidoc.element.antd.Badge.prototype.render)

#### [module antd.Breadcrumb](#apidoc.module.antd.Breadcrumb)
1.  [function <span class="apidocSignatureSpan">antd.</span>Breadcrumb ()](#apidoc.element.antd.Breadcrumb.Breadcrumb)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.</span>Item ()](#apidoc.element.antd.Breadcrumb.Item)
1.  object <span class="apidocSignatureSpan">antd.Breadcrumb.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Breadcrumb.</span>propTypes

#### [module antd.Breadcrumb.Item](#apidoc.module.antd.Breadcrumb.Item)
1.  boolean <span class="apidocSignatureSpan">antd.Breadcrumb.Item.</span>__ANT_BREADCRUMB_ITEM
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.</span>Item ()](#apidoc.element.antd.Breadcrumb.Item.Item)
1.  object <span class="apidocSignatureSpan">antd.Breadcrumb.Item.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Breadcrumb.Item.</span>propTypes

#### [module antd.Breadcrumb.Item.prototype](#apidoc.module.antd.Breadcrumb.Item.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.Item.prototype.</span>render ()](#apidoc.element.antd.Breadcrumb.Item.prototype.render)

#### [module antd.Breadcrumb.propTypes](#apidoc.module.antd.Breadcrumb.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>linkRender ()](#apidoc.element.antd.Breadcrumb.propTypes.linkRender)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>nameRender ()](#apidoc.element.antd.Breadcrumb.propTypes.nameRender)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>params ()](#apidoc.element.antd.Breadcrumb.propTypes.params)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>prefixCls ()](#apidoc.element.antd.Breadcrumb.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>routes ()](#apidoc.element.antd.Breadcrumb.propTypes.routes)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>separator ()](#apidoc.element.antd.Breadcrumb.propTypes.separator)

#### [module antd.Breadcrumb.prototype](#apidoc.module.antd.Breadcrumb.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.prototype.</span>componentDidMount ()](#apidoc.element.antd.Breadcrumb.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Breadcrumb.prototype.</span>render ()](#apidoc.element.antd.Breadcrumb.prototype.render)

#### [module antd.Button](#apidoc.module.antd.Button)
1.  boolean <span class="apidocSignatureSpan">antd.Button.</span>__ANT_BUTTON
1.  [function <span class="apidocSignatureSpan">antd.</span>Button (props)](#apidoc.element.antd.Button.Button)
1.  [function <span class="apidocSignatureSpan">antd.Button.</span>Group (props)](#apidoc.element.antd.Button.Group)
1.  object <span class="apidocSignatureSpan">antd.Button.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Button.</span>propTypes

#### [module antd.Button.propTypes](#apidoc.module.antd.Button.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>className ()](#apidoc.element.antd.Button.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>htmlType ()](#apidoc.element.antd.Button.propTypes.htmlType)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>icon ()](#apidoc.element.antd.Button.propTypes.icon)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>loading ()](#apidoc.element.antd.Button.propTypes.loading)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>onClick ()](#apidoc.element.antd.Button.propTypes.onClick)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>shape ()](#apidoc.element.antd.Button.propTypes.shape)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>size ()](#apidoc.element.antd.Button.propTypes.size)
1.  [function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>type ()](#apidoc.element.antd.Button.propTypes.type)

#### [module antd.Button.prototype](#apidoc.module.antd.Button.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Button.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Button.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Button.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Button.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Button.prototype.</span>render ()](#apidoc.element.antd.Button.prototype.render)

#### [module antd.Calendar](#apidoc.module.antd.Calendar)
1.  [function <span class="apidocSignatureSpan">antd.</span>Calendar (props, context)](#apidoc.element.antd.Calendar.Calendar)
1.  object <span class="apidocSignatureSpan">antd.Calendar.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Calendar.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Calendar.</span>propTypes

#### [module antd.Calendar.contextTypes](#apidoc.module.antd.Calendar.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.contextTypes.</span>antLocale ()](#apidoc.element.antd.Calendar.contextTypes.antLocale)

#### [module antd.Calendar.defaultProps](#apidoc.module.antd.Calendar.defaultProps)
1.  boolean <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>fullscreen
1.  [function <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>onPanelChange ()](#apidoc.element.antd.Calendar.defaultProps.onPanelChange)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>onSelect ()](#apidoc.element.antd.Calendar.defaultProps.onSelect)
1.  object <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>locale
1.  string <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>mode
1.  string <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>prefixCls

#### [module antd.Calendar.propTypes](#apidoc.module.antd.Calendar.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>className ()](#apidoc.element.antd.Calendar.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>dateCellRender ()](#apidoc.element.antd.Calendar.propTypes.dateCellRender)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>dateFullCellRender ()](#apidoc.element.antd.Calendar.propTypes.dateFullCellRender)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>fullscreen ()](#apidoc.element.antd.Calendar.propTypes.fullscreen)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>locale ()](#apidoc.element.antd.Calendar.propTypes.locale)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>monthCellRender ()](#apidoc.element.antd.Calendar.propTypes.monthCellRender)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>monthFullCellRender ()](#apidoc.element.antd.Calendar.propTypes.monthFullCellRender)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>onPanelChange ()](#apidoc.element.antd.Calendar.propTypes.onPanelChange)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>onSelect ()](#apidoc.element.antd.Calendar.propTypes.onSelect)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>prefixCls ()](#apidoc.element.antd.Calendar.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>style ()](#apidoc.element.antd.Calendar.propTypes.style)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>value ()](#apidoc.element.antd.Calendar.propTypes.value)

#### [module antd.Calendar.prototype](#apidoc.module.antd.Calendar.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Calendar.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.prototype.</span>onPanelChange (value, mode)](#apidoc.element.antd.Calendar.prototype.onPanelChange)
1.  [function <span class="apidocSignatureSpan">antd.Calendar.prototype.</span>render ()](#apidoc.element.antd.Calendar.prototype.render)

#### [module antd.Carousel](#apidoc.module.antd.Carousel)
1.  [function <span class="apidocSignatureSpan">antd.</span>Carousel ()](#apidoc.element.antd.Carousel.Carousel)
1.  object <span class="apidocSignatureSpan">antd.Carousel.</span>defaultProps

#### [module antd.Carousel.prototype](#apidoc.module.antd.Carousel.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Carousel.prototype.</span>componentDidMount ()](#apidoc.element.antd.Carousel.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Carousel.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Carousel.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Carousel.prototype.</span>render ()](#apidoc.element.antd.Carousel.prototype.render)

#### [module antd.Cascader](#apidoc.module.antd.Cascader)
1.  [function <span class="apidocSignatureSpan">antd.</span>Cascader (props)](#apidoc.element.antd.Cascader.Cascader)
1.  object <span class="apidocSignatureSpan">antd.Cascader.</span>defaultProps

#### [module antd.Cascader.prototype](#apidoc.module.antd.Cascader.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Cascader.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>flattenTree (options, changeOnSelect)](#apidoc.element.antd.Cascader.prototype.flattenTree)
1.  [function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>generateFilteredOptions (prefixCls)](#apidoc.element.antd.Cascader.prototype.generateFilteredOptions)
1.  [function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>getLabel ()](#apidoc.element.antd.Cascader.prototype.getLabel)
1.  [function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>render ()](#apidoc.element.antd.Cascader.prototype.render)

#### [module antd.Checkbox](#apidoc.module.antd.Checkbox)
1.  [function <span class="apidocSignatureSpan">antd.</span>Checkbox ()](#apidoc.element.antd.Checkbox.Checkbox)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.</span>Group (props)](#apidoc.element.antd.Checkbox.Group)
1.  object <span class="apidocSignatureSpan">antd.Checkbox.</span>defaultProps

#### [module antd.Checkbox.Group](#apidoc.module.antd.Checkbox.Group)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.</span>Group (props)](#apidoc.element.antd.Checkbox.Group.Group)
1.  object <span class="apidocSignatureSpan">antd.Checkbox.Group.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Checkbox.Group.</span>propTypes

#### [module antd.Checkbox.Group.prototype](#apidoc.module.antd.Checkbox.Group.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Checkbox.Group.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>getOptions ()](#apidoc.element.antd.Checkbox.Group.prototype.getOptions)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>render ()](#apidoc.element.antd.Checkbox.Group.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Checkbox.Group.prototype.shouldComponentUpdate)

#### [module antd.Checkbox.prototype](#apidoc.module.antd.Checkbox.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.prototype.</span>render ()](#apidoc.element.antd.Checkbox.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Checkbox.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Checkbox.prototype.shouldComponentUpdate)

#### [module antd.Col](#apidoc.module.antd.Col)
1.  [function <span class="apidocSignatureSpan">antd.</span>Col ()](#apidoc.element.antd.Col.Col)
1.  object <span class="apidocSignatureSpan">antd.Col.</span>propTypes

#### [module antd.Col.propTypes](#apidoc.module.antd.Col.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>children ()](#apidoc.element.antd.Col.propTypes.children)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>className ()](#apidoc.element.antd.Col.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>lg ()](#apidoc.element.antd.Col.propTypes.lg)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>md ()](#apidoc.element.antd.Col.propTypes.md)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>offset ()](#apidoc.element.antd.Col.propTypes.offset)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>order ()](#apidoc.element.antd.Col.propTypes.order)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>pull ()](#apidoc.element.antd.Col.propTypes.pull)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>push ()](#apidoc.element.antd.Col.propTypes.push)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>sm ()](#apidoc.element.antd.Col.propTypes.sm)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>span ()](#apidoc.element.antd.Col.propTypes.span)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>xl ()](#apidoc.element.antd.Col.propTypes.xl)
1.  [function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>xs ()](#apidoc.element.antd.Col.propTypes.xs)

#### [module antd.Col.prototype](#apidoc.module.antd.Col.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Col.prototype.</span>render ()](#apidoc.element.antd.Col.prototype.render)

#### [module antd.Collapse](#apidoc.module.antd.Collapse)
1.  [function <span class="apidocSignatureSpan">antd.</span>Collapse ()](#apidoc.element.antd.Collapse.Collapse)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.</span>Panel (props, context, updater)](#apidoc.element.antd.Collapse.Panel)
1.  object <span class="apidocSignatureSpan">antd.Collapse.</span>defaultProps

#### [module antd.Collapse.Panel](#apidoc.module.antd.Collapse.Panel)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.</span>Panel (props, context, updater)](#apidoc.element.antd.Collapse.Panel.Panel)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.</span>getDefaultProps ()](#apidoc.element.antd.Collapse.Panel.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.</span>propTypes
1.  string <span class="apidocSignatureSpan">antd.Collapse.Panel.</span>displayName

#### [module antd.Collapse.Panel.prototype](#apidoc.module.antd.Collapse.Panel.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Collapse.Panel.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>getDOMNode ()](#apidoc.element.antd.Collapse.Panel.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>handleItemClick ()](#apidoc.element.antd.Collapse.Panel.prototype.handleItemClick)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>render ()](#apidoc.element.antd.Collapse.Panel.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>updateComponent

#### [module antd.Collapse.Panel.prototype.__reactAutoBindMap](#apidoc.module.antd.Collapse.Panel.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Collapse.Panel.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.__reactAutoBindMap.</span>handleItemClick ()](#apidoc.element.antd.Collapse.Panel.prototype.__reactAutoBindMap.handleItemClick)

#### [module antd.Collapse.prototype](#apidoc.module.antd.Collapse.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Collapse.prototype.</span>render ()](#apidoc.element.antd.Collapse.prototype.render)

#### [module antd.DatePicker](#apidoc.module.antd.DatePicker)
1.  [function <span class="apidocSignatureSpan">antd.</span>DatePicker (props, context, updater)](#apidoc.element.antd.DatePicker.DatePicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>Calendar ()](#apidoc.element.antd.DatePicker.Calendar)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>MonthPicker (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>RangePicker (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>getDefaultProps ()](#apidoc.element.antd.DatePicker.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.</span>defaultProps
1.  string <span class="apidocSignatureSpan">antd.DatePicker.</span>displayName

#### [module antd.DatePicker.Calendar](#apidoc.module.antd.DatePicker.Calendar)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>Calendar ()](#apidoc.element.antd.DatePicker.Calendar.Calendar)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.Calendar.</span>defaultProps

#### [module antd.DatePicker.Calendar.prototype](#apidoc.module.antd.DatePicker.Calendar.prototype)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.Calendar.prototype.</span>render ()](#apidoc.element.antd.DatePicker.Calendar.prototype.render)

#### [module antd.DatePicker.MonthPicker](#apidoc.module.antd.DatePicker.MonthPicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>MonthPicker (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker.MonthPicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.</span>getDefaultProps ()](#apidoc.element.antd.DatePicker.MonthPicker.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.</span>defaultProps
1.  string <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.</span>displayName

#### [module antd.DatePicker.MonthPicker.prototype](#apidoc.module.antd.DatePicker.MonthPicker.prototype)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.MonthPicker.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.MonthPicker.prototype.handleOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>render ()](#apidoc.element.antd.DatePicker.MonthPicker.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>updateComponent

#### [module antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap](#apidoc.module.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.handleOpenChange)

#### [module antd.DatePicker.RangePicker](#apidoc.module.antd.DatePicker.RangePicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.</span>RangePicker (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker.RangePicker)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.</span>getDefaultProps ()](#apidoc.element.antd.DatePicker.RangePicker.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.</span>defaultProps
1.  string <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.</span>displayName

#### [module antd.DatePicker.RangePicker.prototype](#apidoc.module.antd.DatePicker.RangePicker.prototype)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.RangePicker.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.RangePicker.prototype.handleOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>render ()](#apidoc.element.antd.DatePicker.RangePicker.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>updateComponent

#### [module antd.DatePicker.RangePicker.prototype.__reactAutoBindMap](#apidoc.module.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.handleOpenChange)

#### [module antd.DatePicker.contextTypes](#apidoc.module.antd.DatePicker.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.contextTypes.</span>antLocale ()](#apidoc.element.antd.DatePicker.contextTypes.antLocale)

#### [module antd.DatePicker.defaultProps](#apidoc.module.antd.DatePicker.defaultProps)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>onChange ()](#apidoc.element.antd.DatePicker.defaultProps.onChange)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>onOk ()](#apidoc.element.antd.DatePicker.defaultProps.onOk)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>onOpenChange ()](#apidoc.element.antd.DatePicker.defaultProps.onOpenChange)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>align
1.  object <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>locale
1.  object <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>popupStyle
1.  string <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>format
1.  string <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>inputPrefixCls
1.  string <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>prefixCls
1.  string <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>transitionName

#### [module antd.DatePicker.prototype](#apidoc.module.antd.DatePicker.prototype)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.DatePicker.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.prototype.handleOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>render ()](#apidoc.element.antd.DatePicker.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>updateComponent

#### [module antd.DatePicker.prototype.__reactAutoBindMap](#apidoc.module.antd.DatePicker.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.DatePicker.prototype.__reactAutoBindMap.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.prototype.__reactAutoBindMap.handleOpenChange)

#### [module antd.Dropdown](#apidoc.module.antd.Dropdown)
1.  [function <span class="apidocSignatureSpan">antd.</span>Dropdown ()](#apidoc.element.antd.Dropdown.Dropdown)
1.  [function <span class="apidocSignatureSpan">antd.Dropdown.</span>Button ()](#apidoc.element.antd.Dropdown.Button)
1.  object <span class="apidocSignatureSpan">antd.Dropdown.</span>defaultProps

#### [module antd.Dropdown.Button](#apidoc.module.antd.Dropdown.Button)
1.  [function <span class="apidocSignatureSpan">antd.Dropdown.</span>Button ()](#apidoc.element.antd.Dropdown.Button.Button)
1.  object <span class="apidocSignatureSpan">antd.Dropdown.Button.</span>defaultProps

#### [module antd.Dropdown.Button.prototype](#apidoc.module.antd.Dropdown.Button.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Dropdown.Button.prototype.</span>render ()](#apidoc.element.antd.Dropdown.Button.prototype.render)

#### [module antd.Dropdown.prototype](#apidoc.module.antd.Dropdown.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Dropdown.prototype.</span>getTransitionName ()](#apidoc.element.antd.Dropdown.prototype.getTransitionName)
1.  [function <span class="apidocSignatureSpan">antd.Dropdown.prototype.</span>render ()](#apidoc.element.antd.Dropdown.prototype.render)

#### [module antd.Form](#apidoc.module.antd.Form)
1.  [function <span class="apidocSignatureSpan">antd.</span>Form (props)](#apidoc.element.antd.Form.Form)
1.  [function <span class="apidocSignatureSpan">antd.Form.</span>Item ()](#apidoc.element.antd.Form.Item)
1.  [function <span class="apidocSignatureSpan">antd.Form.</span>create (options)](#apidoc.element.antd.Form.create)
1.  object <span class="apidocSignatureSpan">antd.Form.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Form.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Form.</span>propTypes

#### [module antd.Form.Item](#apidoc.module.antd.Form.Item)
1.  [function <span class="apidocSignatureSpan">antd.Form.</span>Item ()](#apidoc.element.antd.Form.Item.Item)
1.  object <span class="apidocSignatureSpan">antd.Form.Item.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Form.Item.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Form.Item.</span>propTypes

#### [module antd.Form.Item.prototype](#apidoc.module.antd.Form.Item.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>componentDidMount ()](#apidoc.element.antd.Form.Item.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getChildProp (prop)](#apidoc.element.antd.Form.Item.prototype.getChildProp)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getControls (children, recursively)](#apidoc.element.antd.Form.Item.prototype.getControls)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getHelpMsg ()](#apidoc.element.antd.Form.Item.prototype.getHelpMsg)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getId ()](#apidoc.element.antd.Form.Item.prototype.getId)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getMeta ()](#apidoc.element.antd.Form.Item.prototype.getMeta)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getOnlyControl ()](#apidoc.element.antd.Form.Item.prototype.getOnlyControl)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getValidateStatus ()](#apidoc.element.antd.Form.Item.prototype.getValidateStatus)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>isRequired ()](#apidoc.element.antd.Form.Item.prototype.isRequired)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>render ()](#apidoc.element.antd.Form.Item.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderChildren ()](#apidoc.element.antd.Form.Item.prototype.renderChildren)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderExtra ()](#apidoc.element.antd.Form.Item.prototype.renderExtra)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderFormItem (children)](#apidoc.element.antd.Form.Item.prototype.renderFormItem)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderHelp ()](#apidoc.element.antd.Form.Item.prototype.renderHelp)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderLabel ()](#apidoc.element.antd.Form.Item.prototype.renderLabel)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderValidateWrapper (c1, c2, c3)](#apidoc.element.antd.Form.Item.prototype.renderValidateWrapper)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderWrapper (children)](#apidoc.element.antd.Form.Item.prototype.renderWrapper)
1.  [function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Form.Item.prototype.shouldComponentUpdate)

#### [module antd.Form.childContextTypes](#apidoc.module.antd.Form.childContextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Form.childContextTypes.</span>vertical ()](#apidoc.element.antd.Form.childContextTypes.vertical)

#### [module antd.Form.defaultProps](#apidoc.module.antd.Form.defaultProps)
1.  boolean <span class="apidocSignatureSpan">antd.Form.defaultProps.</span>hideRequiredMark
1.  [function <span class="apidocSignatureSpan">antd.Form.defaultProps.</span>onSubmit (e)](#apidoc.element.antd.Form.defaultProps.onSubmit)
1.  string <span class="apidocSignatureSpan">antd.Form.defaultProps.</span>layout
1.  string <span class="apidocSignatureSpan">antd.Form.defaultProps.</span>prefixCls

#### [module antd.Form.propTypes](#apidoc.module.antd.Form.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>children ()](#apidoc.element.antd.Form.propTypes.children)
1.  [function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>hideRequiredMark ()](#apidoc.element.antd.Form.propTypes.hideRequiredMark)
1.  [function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>layout ()](#apidoc.element.antd.Form.propTypes.layout)
1.  [function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>onSubmit ()](#apidoc.element.antd.Form.propTypes.onSubmit)
1.  [function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>prefixCls ()](#apidoc.element.antd.Form.propTypes.prefixCls)

#### [module antd.Form.prototype](#apidoc.module.antd.Form.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Form.prototype.</span>getChildContext ()](#apidoc.element.antd.Form.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">antd.Form.prototype.</span>render ()](#apidoc.element.antd.Form.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Form.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Form.prototype.shouldComponentUpdate)

#### [module antd.Input](#apidoc.module.antd.Input)
1.  [function <span class="apidocSignatureSpan">antd.</span>Input ()](#apidoc.element.antd.Input.Input)
1.  [function <span class="apidocSignatureSpan">antd.Input.</span>Group (props)](#apidoc.element.antd.Input.Group)
1.  [function <span class="apidocSignatureSpan">antd.Input.</span>Search ()](#apidoc.element.antd.Input.Search)
1.  object <span class="apidocSignatureSpan">antd.Input.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Input.</span>propTypes

#### [module antd.Input.Search](#apidoc.module.antd.Input.Search)
1.  [function <span class="apidocSignatureSpan">antd.Input.</span>Search ()](#apidoc.element.antd.Input.Search.Search)
1.  object <span class="apidocSignatureSpan">antd.Input.Search.</span>defaultProps

#### [module antd.Input.Search.prototype](#apidoc.module.antd.Input.Search.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Input.Search.prototype.</span>render ()](#apidoc.element.antd.Input.Search.prototype.render)

#### [module antd.Input.propTypes](#apidoc.module.antd.Input.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>addonAfter ()](#apidoc.element.antd.Input.propTypes.addonAfter)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>addonBefore ()](#apidoc.element.antd.Input.propTypes.addonBefore)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>autosize ()](#apidoc.element.antd.Input.propTypes.autosize)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>className ()](#apidoc.element.antd.Input.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>defaultValue ()](#apidoc.element.antd.Input.propTypes.defaultValue)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>disabled ()](#apidoc.element.antd.Input.propTypes.disabled)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>id ()](#apidoc.element.antd.Input.propTypes.id)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onBlur ()](#apidoc.element.antd.Input.propTypes.onBlur)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onFocus ()](#apidoc.element.antd.Input.propTypes.onFocus)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onKeyDown ()](#apidoc.element.antd.Input.propTypes.onKeyDown)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onPressEnter ()](#apidoc.element.antd.Input.propTypes.onPressEnter)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>prefix ()](#apidoc.element.antd.Input.propTypes.prefix)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>prefixCls ()](#apidoc.element.antd.Input.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>size ()](#apidoc.element.antd.Input.propTypes.size)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>suffix ()](#apidoc.element.antd.Input.propTypes.suffix)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>type ()](#apidoc.element.antd.Input.propTypes.type)
1.  [function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>value ()](#apidoc.element.antd.Input.propTypes.value)

#### [module antd.Input.prototype](#apidoc.module.antd.Input.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>componentDidMount ()](#apidoc.element.antd.Input.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Input.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>focus ()](#apidoc.element.antd.Input.prototype.focus)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>render ()](#apidoc.element.antd.Input.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>renderInput ()](#apidoc.element.antd.Input.prototype.renderInput)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>renderLabeledIcon (children)](#apidoc.element.antd.Input.prototype.renderLabeledIcon)
1.  [function <span class="apidocSignatureSpan">antd.Input.prototype.</span>renderLabeledInput (children)](#apidoc.element.antd.Input.prototype.renderLabeledInput)

#### [module antd.InputNumber](#apidoc.module.antd.InputNumber)
1.  [function <span class="apidocSignatureSpan">antd.</span>InputNumber ()](#apidoc.element.antd.InputNumber.InputNumber)
1.  object <span class="apidocSignatureSpan">antd.InputNumber.</span>defaultProps

#### [module antd.InputNumber.prototype](#apidoc.module.antd.InputNumber.prototype)
1.  [function <span class="apidocSignatureSpan">antd.InputNumber.prototype.</span>render ()](#apidoc.element.antd.InputNumber.prototype.render)

#### [module antd.Layout](#apidoc.module.antd.Layout)
1.  [function <span class="apidocSignatureSpan">antd.</span>Layout ()](#apidoc.element.antd.Layout.Layout)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Content ()](#apidoc.element.antd.Layout.Content)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Footer ()](#apidoc.element.antd.Layout.Footer)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Header ()](#apidoc.element.antd.Layout.Header)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Sider (props)](#apidoc.element.antd.Layout.Sider)

#### [module antd.Layout.Content](#apidoc.module.antd.Layout.Content)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Content ()](#apidoc.element.antd.Layout.Content.Content)

#### [module antd.Layout.Content.prototype](#apidoc.module.antd.Layout.Content.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Content.prototype.</span>render ()](#apidoc.element.antd.Layout.Content.prototype.render)

#### [module antd.Layout.Footer](#apidoc.module.antd.Layout.Footer)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Footer ()](#apidoc.element.antd.Layout.Footer.Footer)

#### [module antd.Layout.Footer.prototype](#apidoc.module.antd.Layout.Footer.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Footer.prototype.</span>render ()](#apidoc.element.antd.Layout.Footer.prototype.render)

#### [module antd.Layout.Header](#apidoc.module.antd.Layout.Header)
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Header ()](#apidoc.element.antd.Layout.Header.Header)

#### [module antd.Layout.Header.prototype](#apidoc.module.antd.Layout.Header.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Header.prototype.</span>render ()](#apidoc.element.antd.Layout.Header.prototype.render)

#### [module antd.Layout.Sider](#apidoc.module.antd.Layout.Sider)
1.  boolean <span class="apidocSignatureSpan">antd.Layout.Sider.</span>__ANT_LAYOUT_SIDER
1.  [function <span class="apidocSignatureSpan">antd.Layout.</span>Sider (props)](#apidoc.element.antd.Layout.Sider.Sider)
1.  object <span class="apidocSignatureSpan">antd.Layout.Sider.</span>defaultProps

#### [module antd.Layout.Sider.prototype](#apidoc.module.antd.Layout.Sider.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>componentDidMount ()](#apidoc.element.antd.Layout.Sider.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Layout.Sider.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Layout.Sider.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>render ()](#apidoc.element.antd.Layout.Sider.prototype.render)

#### [module antd.Layout.prototype](#apidoc.module.antd.Layout.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Layout.prototype.</span>render ()](#apidoc.element.antd.Layout.prototype.render)

#### [module antd.LocaleProvider](#apidoc.module.antd.LocaleProvider)
1.  [function <span class="apidocSignatureSpan">antd.</span>LocaleProvider ()](#apidoc.element.antd.LocaleProvider.LocaleProvider)
1.  object <span class="apidocSignatureSpan">antd.LocaleProvider.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.LocaleProvider.</span>propTypes

#### [module antd.LocaleProvider.childContextTypes](#apidoc.module.antd.LocaleProvider.childContextTypes)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.childContextTypes.</span>antLocale ()](#apidoc.element.antd.LocaleProvider.childContextTypes.antLocale)

#### [module antd.LocaleProvider.propTypes](#apidoc.module.antd.LocaleProvider.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.propTypes.</span>locale ()](#apidoc.element.antd.LocaleProvider.propTypes.locale)

#### [module antd.LocaleProvider.prototype](#apidoc.module.antd.LocaleProvider.prototype)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.LocaleProvider.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>componentWillMount ()](#apidoc.element.antd.LocaleProvider.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>componentWillUnMount ()](#apidoc.element.antd.LocaleProvider.prototype.componentWillUnMount)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>getChildContext ()](#apidoc.element.antd.LocaleProvider.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>render ()](#apidoc.element.antd.LocaleProvider.prototype.render)

#### [module antd.Mention](#apidoc.module.antd.Mention)
1.  [function <span class="apidocSignatureSpan">antd.</span>Mention {{signature}}](#apidoc.element.antd.Mention.Mention)
1.  [function <span class="apidocSignatureSpan">antd.Mention.</span>Nav ()](#apidoc.element.antd.Mention.Nav)
1.  [function <span class="apidocSignatureSpan">antd.Mention.</span>getMentions (editorState)](#apidoc.element.antd.Mention.getMentions)
1.  [function <span class="apidocSignatureSpan">antd.Mention.</span>toEditorState (text)](#apidoc.element.antd.Mention.toEditorState)
1.  [function <span class="apidocSignatureSpan">antd.Mention.</span>toString (editorState)](#apidoc.element.antd.Mention.toString)
1.  object <span class="apidocSignatureSpan">antd.Mention.</span>defaultProps

#### [module antd.Mention.Nav](#apidoc.module.antd.Mention.Nav)
1.  [function <span class="apidocSignatureSpan">antd.Mention.</span>Nav ()](#apidoc.element.antd.Mention.Nav.Nav)
1.  object <span class="apidocSignatureSpan">antd.Mention.Nav.</span>propTypes

#### [module antd.Mention.Nav.prototype](#apidoc.module.antd.Mention.Nav.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Mention.Nav.prototype.</span>render ()](#apidoc.element.antd.Mention.Nav.prototype.render)

#### [module antd.Mention.prototype](#apidoc.module.antd.Mention.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Mention.prototype.</span>componentWillReceiveProps (_ref)](#apidoc.element.antd.Mention.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Mention.prototype.</span>defaultSearchChange (value)](#apidoc.element.antd.Mention.prototype.defaultSearchChange)
1.  [function <span class="apidocSignatureSpan">antd.Mention.prototype.</span>render ()](#apidoc.element.antd.Mention.prototype.render)

#### [module antd.Menu](#apidoc.module.antd.Menu)
1.  [function <span class="apidocSignatureSpan">antd.</span>Menu (props)](#apidoc.element.antd.Menu.Menu)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>Divider (props, context, updater)](#apidoc.element.antd.Menu.Divider)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>Item (props, context, updater)](#apidoc.element.antd.Menu.Item)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>ItemGroup (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>SubMenu (props, context, updater)](#apidoc.element.antd.Menu.SubMenu)
1.  object <span class="apidocSignatureSpan">antd.Menu.</span>defaultProps

#### [module antd.Menu.Divider](#apidoc.module.antd.Menu.Divider)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>Divider (props, context, updater)](#apidoc.element.antd.Menu.Divider.Divider)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Divider.</span>getDefaultProps ()](#apidoc.element.antd.Menu.Divider.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.</span>propTypes
1.  string <span class="apidocSignatureSpan">antd.Menu.Divider.</span>displayName

#### [module antd.Menu.Divider.prototype](#apidoc.module.antd.Menu.Divider.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.Divider.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.Divider.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>render ()](#apidoc.element.antd.Menu.Divider.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>updateComponent

#### [module antd.Menu.Divider.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.Divider.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.Divider.prototype.__reactAutoBindMap.getDOMNode)

#### [module antd.Menu.Item](#apidoc.module.antd.Menu.Item)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>Item (props, context, updater)](#apidoc.element.antd.Menu.Item.Item)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.</span>getDefaultProps ()](#apidoc.element.antd.Menu.Item.getDefaultProps)
1.  number <span class="apidocSignatureSpan">antd.Menu.Item.</span>isMenuItem
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.</span>propTypes
1.  string <span class="apidocSignatureSpan">antd.Menu.Item.</span>displayName

#### [module antd.Menu.Item.prototype](#apidoc.module.antd.Menu.Item.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>clearMenuItemMouseLeaveTimer ()](#apidoc.element.antd.Menu.Item.prototype.clearMenuItemMouseLeaveTimer)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Menu.Item.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.Item.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getActiveClassName ()](#apidoc.element.antd.Menu.Item.prototype.getActiveClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.Item.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.Item.prototype.getDisabledClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getPrefixCls ()](#apidoc.element.antd.Menu.Item.prototype.getPrefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.Item.prototype.getSelectedClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>isSelected ()](#apidoc.element.antd.Menu.Item.prototype.isSelected)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onClick (e)](#apidoc.element.antd.Menu.Item.prototype.onClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onKeyDown (e)](#apidoc.element.antd.Menu.Item.prototype.onKeyDown)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.Item.prototype.onMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.Item.prototype.onMouseLeave)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>render ()](#apidoc.element.antd.Menu.Item.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>updateComponent

#### [module antd.Menu.Item.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.Item.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>clearMenuItemMouseLeaveTimer ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.clearMenuItemMouseLeaveTimer)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getActiveClassName ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getActiveClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getDisabledClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getPrefixCls ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getPrefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getSelectedClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>isSelected ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.isSelected)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onClick (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onKeyDown (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onKeyDown)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onMouseLeave)

#### [module antd.Menu.ItemGroup](#apidoc.module.antd.Menu.ItemGroup)
1.  boolean <span class="apidocSignatureSpan">antd.Menu.ItemGroup.</span>isMenuItemGroup
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>ItemGroup (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup.ItemGroup)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.</span>getDefaultProps ()](#apidoc.element.antd.Menu.ItemGroup.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.</span>propTypes
1.  string <span class="apidocSignatureSpan">antd.Menu.ItemGroup.</span>displayName

#### [module antd.Menu.ItemGroup.prototype](#apidoc.module.antd.Menu.ItemGroup.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.ItemGroup.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>render ()](#apidoc.element.antd.Menu.ItemGroup.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>renderInnerMenuItem (item, subIndex)](#apidoc.element.antd.Menu.ItemGroup.prototype.renderInnerMenuItem)
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>updateComponent

#### [module antd.Menu.ItemGroup.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.ItemGroup.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.ItemGroup.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.__reactAutoBindMap.</span>renderInnerMenuItem (item, subIndex)](#apidoc.element.antd.Menu.ItemGroup.prototype.__reactAutoBindMap.renderInnerMenuItem)

#### [module antd.Menu.SubMenu](#apidoc.module.antd.Menu.SubMenu)
1.  [function <span class="apidocSignatureSpan">antd.Menu.</span>SubMenu (props, context, updater)](#apidoc.element.antd.Menu.SubMenu.SubMenu)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.</span>getDefaultProps ()](#apidoc.element.antd.Menu.SubMenu.getDefaultProps)
1.  number <span class="apidocSignatureSpan">antd.Menu.SubMenu.</span>isSubMenu
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.</span>propTypes
1.  string <span class="apidocSignatureSpan">antd.Menu.SubMenu.</span>displayName

#### [module antd.Menu.SubMenu.prototype](#apidoc.module.antd.Menu.SubMenu.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>addKeyPath (info)](#apidoc.element.antd.Menu.SubMenu.prototype.addKeyPath)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>bindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.bindRootCloseHandlers)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>clearSubMenuLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuLeaveTimer)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>clearSubMenuTimers ()](#apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuTimers)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>clearSubMenuTitleLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuTitleLeaveTimer)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentDidMount ()](#apidoc.element.antd.Menu.SubMenu.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.Menu.SubMenu.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Menu.SubMenu.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.SubMenu.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getActiveClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getActiveClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.SubMenu.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getDisabledClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getInitialState ()](#apidoc.element.antd.Menu.SubMenu.prototype.getInitialState)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getOpenClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getOpenClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getPrefixCls ()](#apidoc.element.antd.Menu.SubMenu.prototype.getPrefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getSelectedClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>handleDocumentClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.handleDocumentClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>handleDocumentKeyUp (e)](#apidoc.element.antd.Menu.SubMenu.prototype.handleDocumentKeyUp)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>isChildrenSelected ()](#apidoc.element.antd.Menu.SubMenu.prototype.isChildrenSelected)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>isOpen ()](#apidoc.element.antd.Menu.SubMenu.prototype.isOpen)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onDeselect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.onDeselect)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onDestroy (key)](#apidoc.element.antd.Menu.SubMenu.prototype.onDestroy)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onKeyDown (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onKeyDown)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onMouseLeave)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onOpenChange (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onSelect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.onSelect)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onSubMenuClick (info)](#apidoc.element.antd.Menu.SubMenu.prototype.onSubMenuClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onTitleClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onTitleClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onTitleMouseEnter (domEvent)](#apidoc.element.antd.Menu.SubMenu.prototype.onTitleMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onTitleMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onTitleMouseLeave)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>render ()](#apidoc.element.antd.Menu.SubMenu.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>renderChildren (children)](#apidoc.element.antd.Menu.SubMenu.prototype.renderChildren)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>saveMenuInstance (c)](#apidoc.element.antd.Menu.SubMenu.prototype.saveMenuInstance)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>triggerOpenChange (open, type)](#apidoc.element.antd.Menu.SubMenu.prototype.triggerOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>unbindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.unbindRootCloseHandlers)
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>updateComponent

#### [module antd.Menu.SubMenu.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.SubMenu.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>addKeyPath (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.addKeyPath)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>bindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.bindRootCloseHandlers)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>clearSubMenuLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuLeaveTimer)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>clearSubMenuTimers ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuTimers)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>clearSubMenuTitleLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuTitleLeaveTimer)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getActiveClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getActiveClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getDisabledClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getOpenClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getOpenClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getPrefixCls ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getPrefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getSelectedClassName)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>handleDocumentClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.handleDocumentClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>handleDocumentKeyUp (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.handleDocumentKeyUp)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>isChildrenSelected ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.isChildrenSelected)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>isOpen ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.isOpen)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onDeselect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onDeselect)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onDestroy (key)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onDestroy)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onKeyDown (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onKeyDown)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onMouseLeave)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onOpenChange (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onSelect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onSelect)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onSubMenuClick (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onSubMenuClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onTitleClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleClick)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onTitleMouseEnter (domEvent)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onTitleMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleMouseLeave)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>renderChildren (children)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.renderChildren)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>saveMenuInstance (c)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.saveMenuInstance)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>triggerOpenChange (open, type)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.triggerOpenChange)
1.  [function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>unbindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.unbindRootCloseHandlers)

#### [module antd.Menu.prototype](#apidoc.module.antd.Menu.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Menu.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Menu.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Menu.prototype.</span>render ()](#apidoc.element.antd.Menu.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Menu.prototype.</span>setOpenKeys (openKeys)](#apidoc.element.antd.Menu.prototype.setOpenKeys)

#### [module antd.Modal](#apidoc.module.antd.Modal)
1.  [function <span class="apidocSignatureSpan">antd.</span>Modal ()](#apidoc.element.antd.Modal.Modal)
1.  [function <span class="apidocSignatureSpan">antd.Modal.</span>confirm (props)](#apidoc.element.antd.Modal.confirm)
1.  [function <span class="apidocSignatureSpan">antd.Modal.</span>error (props)](#apidoc.element.antd.Modal.error)
1.  [function <span class="apidocSignatureSpan">antd.Modal.</span>info (props)](#apidoc.element.antd.Modal.info)
1.  [function <span class="apidocSignatureSpan">antd.Modal.</span>success (props)](#apidoc.element.antd.Modal.success)
1.  [function <span class="apidocSignatureSpan">antd.Modal.</span>warn (props)](#apidoc.element.antd.Modal.warn)
1.  [function <span class="apidocSignatureSpan">antd.Modal.</span>warning (props)](#apidoc.element.antd.Modal.warning)
1.  object <span class="apidocSignatureSpan">antd.Modal.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Modal.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Modal.</span>propTypes

#### [module antd.Modal.contextTypes](#apidoc.module.antd.Modal.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Modal.contextTypes.</span>antLocale ()](#apidoc.element.antd.Modal.contextTypes.antLocale)

#### [module antd.Modal.propTypes](#apidoc.module.antd.Modal.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>align ()](#apidoc.element.antd.Modal.propTypes.align)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>cancelText ()](#apidoc.element.antd.Modal.propTypes.cancelText)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>closable ()](#apidoc.element.antd.Modal.propTypes.closable)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>confirmLoading ()](#apidoc.element.antd.Modal.propTypes.confirmLoading)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>footer ()](#apidoc.element.antd.Modal.propTypes.footer)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>okText ()](#apidoc.element.antd.Modal.propTypes.okText)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>onCancel ()](#apidoc.element.antd.Modal.propTypes.onCancel)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>onOk ()](#apidoc.element.antd.Modal.propTypes.onOk)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>prefixCls ()](#apidoc.element.antd.Modal.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>title ()](#apidoc.element.antd.Modal.propTypes.title)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>visible ()](#apidoc.element.antd.Modal.propTypes.visible)
1.  [function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>width ()](#apidoc.element.antd.Modal.propTypes.width)

#### [module antd.Modal.prototype](#apidoc.module.antd.Modal.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Modal.prototype.</span>componentDidMount ()](#apidoc.element.antd.Modal.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Modal.prototype.</span>render ()](#apidoc.element.antd.Modal.prototype.render)

#### [module antd.Pagination](#apidoc.module.antd.Pagination)
1.  [function <span class="apidocSignatureSpan">antd.</span>Pagination ()](#apidoc.element.antd.Pagination.Pagination)
1.  object <span class="apidocSignatureSpan">antd.Pagination.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Pagination.</span>defaultProps

#### [module antd.Pagination.contextTypes](#apidoc.module.antd.Pagination.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Pagination.contextTypes.</span>antLocale ()](#apidoc.element.antd.Pagination.contextTypes.antLocale)

#### [module antd.Pagination.prototype](#apidoc.module.antd.Pagination.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Pagination.prototype.</span>getLocale ()](#apidoc.element.antd.Pagination.prototype.getLocale)

#### [module antd.Popconfirm](#apidoc.module.antd.Popconfirm)
1.  [function <span class="apidocSignatureSpan">antd.</span>Popconfirm ()](#apidoc.element.antd.Popconfirm.Popconfirm)
1.  object <span class="apidocSignatureSpan">antd.Popconfirm.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Popconfirm.</span>defaultProps

#### [module antd.Popconfirm.contextTypes](#apidoc.module.antd.Popconfirm.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Popconfirm.contextTypes.</span>antLocale ()](#apidoc.element.antd.Popconfirm.contextTypes.antLocale)

#### [module antd.Popconfirm.prototype](#apidoc.module.antd.Popconfirm.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Popconfirm.prototype.</span>getLocale ()](#apidoc.element.antd.Popconfirm.prototype.getLocale)

#### [module antd.Popover](#apidoc.module.antd.Popover)
1.  [function <span class="apidocSignatureSpan">antd.</span>Popover ()](#apidoc.element.antd.Popover.Popover)
1.  object <span class="apidocSignatureSpan">antd.Popover.</span>defaultProps

#### [module antd.Popover.prototype](#apidoc.module.antd.Popover.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Popover.prototype.</span>getOverlay ()](#apidoc.element.antd.Popover.prototype.getOverlay)
1.  [function <span class="apidocSignatureSpan">antd.Popover.prototype.</span>getPopupDomNode ()](#apidoc.element.antd.Popover.prototype.getPopupDomNode)
1.  [function <span class="apidocSignatureSpan">antd.Popover.prototype.</span>render ()](#apidoc.element.antd.Popover.prototype.render)

#### [module antd.Progress](#apidoc.module.antd.Progress)
1.  [function <span class="apidocSignatureSpan">antd.</span>Progress ()](#apidoc.element.antd.Progress.Progress)
1.  object <span class="apidocSignatureSpan">antd.Progress.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Progress.</span>propTypes

#### [module antd.Progress.propTypes](#apidoc.module.antd.Progress.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>format ()](#apidoc.element.antd.Progress.propTypes.format)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>gapDegree ()](#apidoc.element.antd.Progress.propTypes.gapDegree)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>percent ()](#apidoc.element.antd.Progress.propTypes.percent)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>showInfo ()](#apidoc.element.antd.Progress.propTypes.showInfo)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>status ()](#apidoc.element.antd.Progress.propTypes.status)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>strokeWidth ()](#apidoc.element.antd.Progress.propTypes.strokeWidth)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>trailColor ()](#apidoc.element.antd.Progress.propTypes.trailColor)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>type ()](#apidoc.element.antd.Progress.propTypes.type)
1.  [function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>width ()](#apidoc.element.antd.Progress.propTypes.width)

#### [module antd.Progress.prototype](#apidoc.module.antd.Progress.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Progress.prototype.</span>render ()](#apidoc.element.antd.Progress.prototype.render)

#### [module antd.Radio](#apidoc.module.antd.Radio)
1.  [function <span class="apidocSignatureSpan">antd.</span>Radio ()](#apidoc.element.antd.Radio.Radio)
1.  [function <span class="apidocSignatureSpan">antd.Radio.</span>Button ()](#apidoc.element.antd.Radio.Button)
1.  [function <span class="apidocSignatureSpan">antd.Radio.</span>Group (props)](#apidoc.element.antd.Radio.Group)
1.  object <span class="apidocSignatureSpan">antd.Radio.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Radio.</span>defaultProps

#### [module antd.Radio.Button](#apidoc.module.antd.Radio.Button)
1.  [function <span class="apidocSignatureSpan">antd.Radio.</span>Button ()](#apidoc.element.antd.Radio.Button.Button)
1.  object <span class="apidocSignatureSpan">antd.Radio.Button.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Radio.Button.</span>defaultProps

#### [module antd.Radio.Button.prototype](#apidoc.module.antd.Radio.Button.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Radio.Button.prototype.</span>render ()](#apidoc.element.antd.Radio.Button.prototype.render)

#### [module antd.Radio.Group](#apidoc.module.antd.Radio.Group)
1.  [function <span class="apidocSignatureSpan">antd.Radio.</span>Group (props)](#apidoc.element.antd.Radio.Group.Group)
1.  object <span class="apidocSignatureSpan">antd.Radio.Group.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Radio.Group.</span>defaultProps

#### [module antd.Radio.Group.prototype](#apidoc.module.antd.Radio.Group.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Radio.Group.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>getChildContext ()](#apidoc.element.antd.Radio.Group.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>render ()](#apidoc.element.antd.Radio.Group.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>shouldComponentUpdate (nextProps, nextState, nextContext)](#apidoc.element.antd.Radio.Group.prototype.shouldComponentUpdate)

#### [module antd.Radio.contextTypes](#apidoc.module.antd.Radio.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Radio.contextTypes.</span>radioGroup ()](#apidoc.element.antd.Radio.contextTypes.radioGroup)

#### [module antd.Radio.prototype](#apidoc.module.antd.Radio.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Radio.prototype.</span>render ()](#apidoc.element.antd.Radio.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Radio.prototype.</span>shouldComponentUpdate (nextProps, nextState, nextContext)](#apidoc.element.antd.Radio.prototype.shouldComponentUpdate)

#### [module antd.Rate](#apidoc.module.antd.Rate)
1.  [function <span class="apidocSignatureSpan">antd.</span>Rate ()](#apidoc.element.antd.Rate.Rate)
1.  object <span class="apidocSignatureSpan">antd.Rate.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Rate.</span>propTypes

#### [module antd.Rate.propTypes](#apidoc.module.antd.Rate.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Rate.propTypes.</span>character ()](#apidoc.element.antd.Rate.propTypes.character)
1.  [function <span class="apidocSignatureSpan">antd.Rate.propTypes.</span>prefixCls ()](#apidoc.element.antd.Rate.propTypes.prefixCls)

#### [module antd.Rate.prototype](#apidoc.module.antd.Rate.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Rate.prototype.</span>render ()](#apidoc.element.antd.Rate.prototype.render)

#### [module antd.Row](#apidoc.module.antd.Row)
1.  [function <span class="apidocSignatureSpan">antd.</span>Row ()](#apidoc.element.antd.Row.Row)
1.  object <span class="apidocSignatureSpan">antd.Row.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Row.</span>propTypes

#### [module antd.Row.propTypes](#apidoc.module.antd.Row.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>align ()](#apidoc.element.antd.Row.propTypes.align)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>children ()](#apidoc.element.antd.Row.propTypes.children)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>className ()](#apidoc.element.antd.Row.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>gutter ()](#apidoc.element.antd.Row.propTypes.gutter)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>justify ()](#apidoc.element.antd.Row.propTypes.justify)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>prefixCls ()](#apidoc.element.antd.Row.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>type ()](#apidoc.element.antd.Row.propTypes.type)

#### [module antd.Row.prototype](#apidoc.module.antd.Row.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Row.prototype.</span>render ()](#apidoc.element.antd.Row.prototype.render)

#### [module antd.Select](#apidoc.module.antd.Select)
1.  [function <span class="apidocSignatureSpan">antd.</span>Select ()](#apidoc.element.antd.Select.Select)
1.  [function <span class="apidocSignatureSpan">antd.Select.</span>OptGroup ()](#apidoc.element.antd.Select.OptGroup)
1.  [function <span class="apidocSignatureSpan">antd.Select.</span>Option ()](#apidoc.element.antd.Select.Option)
1.  object <span class="apidocSignatureSpan">antd.Select.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Select.</span>propTypes

#### [module antd.Select.propTypes](#apidoc.module.antd.Select.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>choiceTransitionName ()](#apidoc.element.antd.Select.propTypes.choiceTransitionName)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>className ()](#apidoc.element.antd.Select.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>combobox ()](#apidoc.element.antd.Select.propTypes.combobox)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>notFoundContent ()](#apidoc.element.antd.Select.propTypes.notFoundContent)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>optionLabelProp ()](#apidoc.element.antd.Select.propTypes.optionLabelProp)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>prefixCls ()](#apidoc.element.antd.Select.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>showSearch ()](#apidoc.element.antd.Select.propTypes.showSearch)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>size ()](#apidoc.element.antd.Select.propTypes.size)
1.  [function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>transitionName ()](#apidoc.element.antd.Select.propTypes.transitionName)

#### [module antd.Select.prototype](#apidoc.module.antd.Select.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Select.prototype.</span>getLocale ()](#apidoc.element.antd.Select.prototype.getLocale)
1.  [function <span class="apidocSignatureSpan">antd.Select.prototype.</span>render ()](#apidoc.element.antd.Select.prototype.render)

#### [module antd.Slider](#apidoc.module.antd.Slider)
1.  [function <span class="apidocSignatureSpan">antd.</span>Slider (props)](#apidoc.element.antd.Slider.Slider)
1.  object <span class="apidocSignatureSpan">antd.Slider.</span>defaultProps

#### [module antd.Slider.defaultProps](#apidoc.module.antd.Slider.defaultProps)
1.  [function <span class="apidocSignatureSpan">antd.Slider.defaultProps.</span>tipFormatter (value)](#apidoc.element.antd.Slider.defaultProps.tipFormatter)
1.  string <span class="apidocSignatureSpan">antd.Slider.defaultProps.</span>prefixCls
1.  string <span class="apidocSignatureSpan">antd.Slider.defaultProps.</span>tooltipPrefixCls

#### [module antd.Slider.prototype](#apidoc.module.antd.Slider.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Slider.prototype.</span>render ()](#apidoc.element.antd.Slider.prototype.render)

#### [module antd.Spin](#apidoc.module.antd.Spin)
1.  [function <span class="apidocSignatureSpan">antd.</span>Spin (props)](#apidoc.element.antd.Spin.Spin)
1.  object <span class="apidocSignatureSpan">antd.Spin.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Spin.</span>propTypes

#### [module antd.Spin.propTypes](#apidoc.module.antd.Spin.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>className ()](#apidoc.element.antd.Spin.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>prefixCls ()](#apidoc.element.antd.Spin.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>size ()](#apidoc.element.antd.Spin.propTypes.size)
1.  [function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>spinning ()](#apidoc.element.antd.Spin.propTypes.spinning)
1.  [function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>wrapperClassName ()](#apidoc.element.antd.Spin.propTypes.wrapperClassName)

#### [module antd.Spin.prototype](#apidoc.module.antd.Spin.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>componentDidMount ()](#apidoc.element.antd.Spin.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Spin.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Spin.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>isNestedPattern ()](#apidoc.element.antd.Spin.prototype.isNestedPattern)
1.  [function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>render ()](#apidoc.element.antd.Spin.prototype.render)

#### [module antd.Steps](#apidoc.module.antd.Steps)
1.  [function <span class="apidocSignatureSpan">antd.</span>Steps ()](#apidoc.element.antd.Steps.Steps)
1.  [function <span class="apidocSignatureSpan">antd.Steps.</span>Step ()](#apidoc.element.antd.Steps.Step)
1.  object <span class="apidocSignatureSpan">antd.Steps.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Steps.</span>propTypes

#### [module antd.Steps.Step](#apidoc.module.antd.Steps.Step)
1.  [function <span class="apidocSignatureSpan">antd.Steps.</span>Step ()](#apidoc.element.antd.Steps.Step.Step)
1.  object <span class="apidocSignatureSpan">antd.Steps.Step.</span>propTypes

#### [module antd.Steps.Step.prototype](#apidoc.module.antd.Steps.Step.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Steps.Step.prototype.</span>render ()](#apidoc.element.antd.Steps.Step.prototype.render)

#### [module antd.Steps.propTypes](#apidoc.module.antd.Steps.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Steps.propTypes.</span>current ()](#apidoc.element.antd.Steps.propTypes.current)
1.  [function <span class="apidocSignatureSpan">antd.Steps.propTypes.</span>iconPrefix ()](#apidoc.element.antd.Steps.propTypes.iconPrefix)
1.  [function <span class="apidocSignatureSpan">antd.Steps.propTypes.</span>prefixCls ()](#apidoc.element.antd.Steps.propTypes.prefixCls)

#### [module antd.Steps.prototype](#apidoc.module.antd.Steps.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Steps.prototype.</span>render ()](#apidoc.element.antd.Steps.prototype.render)

#### [module antd.Switch](#apidoc.module.antd.Switch)
1.  [function <span class="apidocSignatureSpan">antd.</span>Switch ()](#apidoc.element.antd.Switch.Switch)
1.  object <span class="apidocSignatureSpan">antd.Switch.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Switch.</span>propTypes

#### [module antd.Switch.propTypes](#apidoc.module.antd.Switch.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Switch.propTypes.</span>className ()](#apidoc.element.antd.Switch.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Switch.propTypes.</span>prefixCls ()](#apidoc.element.antd.Switch.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Switch.propTypes.</span>size ()](#apidoc.element.antd.Switch.propTypes.size)

#### [module antd.Switch.prototype](#apidoc.module.antd.Switch.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Switch.prototype.</span>render ()](#apidoc.element.antd.Switch.prototype.render)

#### [module antd.Table](#apidoc.module.antd.Table)
1.  [function <span class="apidocSignatureSpan">antd.</span>Table (props)](#apidoc.element.antd.Table.Table)
1.  [function <span class="apidocSignatureSpan">antd.Table.</span>Column ()](#apidoc.element.antd.Table.Column)
1.  [function <span class="apidocSignatureSpan">antd.Table.</span>ColumnGroup ()](#apidoc.element.antd.Table.ColumnGroup)
1.  object <span class="apidocSignatureSpan">antd.Table.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Table.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Table.</span>propTypes

#### [module antd.Table.contextTypes](#apidoc.module.antd.Table.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Table.contextTypes.</span>antLocale ()](#apidoc.element.antd.Table.contextTypes.antLocale)

#### [module antd.Table.propTypes](#apidoc.module.antd.Table.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>bordered ()](#apidoc.element.antd.Table.propTypes.bordered)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>className ()](#apidoc.element.antd.Table.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>columns ()](#apidoc.element.antd.Table.propTypes.columns)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>dataSource ()](#apidoc.element.antd.Table.propTypes.dataSource)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>dropdownPrefixCls ()](#apidoc.element.antd.Table.propTypes.dropdownPrefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>loading ()](#apidoc.element.antd.Table.propTypes.loading)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>locale ()](#apidoc.element.antd.Table.propTypes.locale)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>onChange ()](#apidoc.element.antd.Table.propTypes.onChange)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>prefixCls ()](#apidoc.element.antd.Table.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>rowSelection ()](#apidoc.element.antd.Table.propTypes.rowSelection)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>size ()](#apidoc.element.antd.Table.propTypes.size)
1.  [function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>useFixedHeader ()](#apidoc.element.antd.Table.propTypes.useFixedHeader)

#### [module antd.Table.prototype](#apidoc.module.antd.Table.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Table.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>findColumn (myKey)](#apidoc.element.antd.Table.prototype.findColumn)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getColumnKey (column, index)](#apidoc.element.antd.Table.prototype.getColumnKey)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getCurrentPageData ()](#apidoc.element.antd.Table.prototype.getCurrentPageData)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getDefaultPagination (props)](#apidoc.element.antd.Table.prototype.getDefaultPagination)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getDefaultSelection ()](#apidoc.element.antd.Table.prototype.getDefaultSelection)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFilteredValueColumns (columns)](#apidoc.element.antd.Table.prototype.getFilteredValueColumns)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFiltersFromColumns (columns)](#apidoc.element.antd.Table.prototype.getFiltersFromColumns)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFlatCurrentPageData ()](#apidoc.element.antd.Table.prototype.getFlatCurrentPageData)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFlatData ()](#apidoc.element.antd.Table.prototype.getFlatData)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getLocalData ()](#apidoc.element.antd.Table.prototype.getLocalData)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getLocale ()](#apidoc.element.antd.Table.prototype.getLocale)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getMaxCurrent (total)](#apidoc.element.antd.Table.prototype.getMaxCurrent)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getSortOrderColumns (columns)](#apidoc.element.antd.Table.prototype.getSortOrderColumns)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getSortStateFromColumns (columns)](#apidoc.element.antd.Table.prototype.getSortStateFromColumns)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getSorterFn ()](#apidoc.element.antd.Table.prototype.getSorterFn)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>hasPagination (props)](#apidoc.element.antd.Table.prototype.hasPagination)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>isFiltersChanged (filters)](#apidoc.element.antd.Table.prototype.isFiltersChanged)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>isSortColumn (column)](#apidoc.element.antd.Table.prototype.isSortColumn)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>prepareParamsArguments (state)](#apidoc.element.antd.Table.prototype.prepareParamsArguments)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>recursiveSort (data, sorterFn)](#apidoc.element.antd.Table.prototype.recursiveSort)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>render ()](#apidoc.element.antd.Table.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>renderColumnsDropdown (columns)](#apidoc.element.antd.Table.prototype.renderColumnsDropdown)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>renderPagination ()](#apidoc.element.antd.Table.prototype.renderPagination)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>renderRowSelection ()](#apidoc.element.antd.Table.prototype.renderRowSelection)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>setSelectedRowKeys (selectedRowKeys, _ref)](#apidoc.element.antd.Table.prototype.setSelectedRowKeys)
1.  [function <span class="apidocSignatureSpan">antd.Table.prototype.</span>toggleSortOrder (order, column)](#apidoc.element.antd.Table.prototype.toggleSortOrder)

#### [module antd.Tabs](#apidoc.module.antd.Tabs)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tabs ()](#apidoc.element.antd.Tabs.Tabs)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.</span>TabPane (props, context, updater)](#apidoc.element.antd.Tabs.TabPane)
1.  object <span class="apidocSignatureSpan">antd.Tabs.</span>defaultProps

#### [module antd.Tabs.TabPane](#apidoc.module.antd.Tabs.TabPane)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.</span>TabPane (props, context, updater)](#apidoc.element.antd.Tabs.TabPane.TabPane)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.TabPane.</span>getDefaultProps ()](#apidoc.element.antd.Tabs.TabPane.getDefaultProps)
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.</span>propTypes
1.  string <span class="apidocSignatureSpan">antd.Tabs.TabPane.</span>displayName

#### [module antd.Tabs.TabPane.prototype](#apidoc.module.antd.Tabs.TabPane.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Tabs.TabPane.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>getDOMNode ()](#apidoc.element.antd.Tabs.TabPane.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>render ()](#apidoc.element.antd.Tabs.TabPane.prototype.render)
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>componentDidMount
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>componentDidUpdate
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>componentWillMount
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>componentWillUpdate
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>getChildContext
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>getInitialState
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>updateComponent

#### [module antd.Tabs.TabPane.prototype.__reactAutoBindMap](#apidoc.module.antd.Tabs.TabPane.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Tabs.TabPane.prototype.__reactAutoBindMap.getDOMNode)

#### [module antd.Tabs.prototype](#apidoc.module.antd.Tabs.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.prototype.</span>componentDidMount ()](#apidoc.element.antd.Tabs.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Tabs.prototype.</span>render ()](#apidoc.element.antd.Tabs.prototype.render)

#### [module antd.Tag](#apidoc.module.antd.Tag)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tag (props)](#apidoc.element.antd.Tag.Tag)
1.  [function <span class="apidocSignatureSpan">antd.Tag.</span>CheckableTag ()](#apidoc.element.antd.Tag.CheckableTag)
1.  object <span class="apidocSignatureSpan">antd.Tag.</span>defaultProps

#### [module antd.Tag.CheckableTag](#apidoc.module.antd.Tag.CheckableTag)
1.  [function <span class="apidocSignatureSpan">antd.Tag.</span>CheckableTag ()](#apidoc.element.antd.Tag.CheckableTag.CheckableTag)

#### [module antd.Tag.CheckableTag.prototype](#apidoc.module.antd.Tag.CheckableTag.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tag.CheckableTag.prototype.</span>render ()](#apidoc.element.antd.Tag.CheckableTag.prototype.render)

#### [module antd.Tag.prototype](#apidoc.module.antd.Tag.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tag.prototype.</span>isPresetColor (color)](#apidoc.element.antd.Tag.prototype.isPresetColor)
1.  [function <span class="apidocSignatureSpan">antd.Tag.prototype.</span>render ()](#apidoc.element.antd.Tag.prototype.render)

#### [module antd.TimePicker](#apidoc.module.antd.TimePicker)
1.  [function <span class="apidocSignatureSpan">antd.</span>TimePicker ()](#apidoc.element.antd.TimePicker.TimePicker)
1.  object <span class="apidocSignatureSpan">antd.TimePicker.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.TimePicker.</span>defaultProps

#### [module antd.TimePicker.contextTypes](#apidoc.module.antd.TimePicker.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.TimePicker.contextTypes.</span>antLocale ()](#apidoc.element.antd.TimePicker.contextTypes.antLocale)

#### [module antd.TimePicker.prototype](#apidoc.module.antd.TimePicker.prototype)
1.  [function <span class="apidocSignatureSpan">antd.TimePicker.prototype.</span>getLocale ()](#apidoc.element.antd.TimePicker.prototype.getLocale)

#### [module antd.Timeline](#apidoc.module.antd.Timeline)
1.  [function <span class="apidocSignatureSpan">antd.</span>Timeline ()](#apidoc.element.antd.Timeline.Timeline)
1.  [function <span class="apidocSignatureSpan">antd.Timeline.</span>Item ()](#apidoc.element.antd.Timeline.Item)
1.  object <span class="apidocSignatureSpan">antd.Timeline.</span>defaultProps

#### [module antd.Timeline.Item](#apidoc.module.antd.Timeline.Item)
1.  [function <span class="apidocSignatureSpan">antd.Timeline.</span>Item ()](#apidoc.element.antd.Timeline.Item.Item)
1.  object <span class="apidocSignatureSpan">antd.Timeline.Item.</span>defaultProps

#### [module antd.Timeline.Item.prototype](#apidoc.module.antd.Timeline.Item.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Timeline.Item.prototype.</span>render ()](#apidoc.element.antd.Timeline.Item.prototype.render)

#### [module antd.Timeline.prototype](#apidoc.module.antd.Timeline.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Timeline.prototype.</span>render ()](#apidoc.element.antd.Timeline.prototype.render)

#### [module antd.Tooltip](#apidoc.module.antd.Tooltip)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tooltip (props)](#apidoc.element.antd.Tooltip.Tooltip)
1.  object <span class="apidocSignatureSpan">antd.Tooltip.</span>defaultProps

#### [module antd.Tooltip.prototype](#apidoc.module.antd.Tooltip.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Tooltip.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>getDisabledCompatibleChildren (element)](#apidoc.element.antd.Tooltip.prototype.getDisabledCompatibleChildren)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>getPlacements ()](#apidoc.element.antd.Tooltip.prototype.getPlacements)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>getPopupDomNode ()](#apidoc.element.antd.Tooltip.prototype.getPopupDomNode)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>isHoverTrigger ()](#apidoc.element.antd.Tooltip.prototype.isHoverTrigger)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>isNoTitle ()](#apidoc.element.antd.Tooltip.prototype.isNoTitle)
1.  [function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>render ()](#apidoc.element.antd.Tooltip.prototype.render)

#### [module antd.Transfer](#apidoc.module.antd.Transfer)
1.  [function <span class="apidocSignatureSpan">antd.</span>Transfer ()](#apidoc.element.antd.Transfer.Transfer)
1.  object <span class="apidocSignatureSpan">antd.Transfer.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Transfer.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Transfer.</span>propTypes

#### [module antd.Transfer.contextTypes](#apidoc.module.antd.Transfer.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.contextTypes.</span>antLocale ()](#apidoc.element.antd.Transfer.contextTypes.antLocale)

#### [module antd.Transfer.defaultProps](#apidoc.module.antd.Transfer.defaultProps)
1.  boolean <span class="apidocSignatureSpan">antd.Transfer.defaultProps.</span>showSearch
1.  [function <span class="apidocSignatureSpan">antd.Transfer.defaultProps.</span>render ()](#apidoc.element.antd.Transfer.defaultProps.render)
1.  object <span class="apidocSignatureSpan">antd.Transfer.defaultProps.</span>dataSource

#### [module antd.Transfer.propTypes](#apidoc.module.antd.Transfer.propTypes)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>body ()](#apidoc.element.antd.Transfer.propTypes.body)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>className ()](#apidoc.element.antd.Transfer.propTypes.className)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>dataSource ()](#apidoc.element.antd.Transfer.propTypes.dataSource)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>filterOption ()](#apidoc.element.antd.Transfer.propTypes.filterOption)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>footer ()](#apidoc.element.antd.Transfer.propTypes.footer)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>height ()](#apidoc.element.antd.Transfer.propTypes.height)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>lazy ()](#apidoc.element.antd.Transfer.propTypes.lazy)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>listStyle ()](#apidoc.element.antd.Transfer.propTypes.listStyle)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>notFoundContent ()](#apidoc.element.antd.Transfer.propTypes.notFoundContent)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>onChange ()](#apidoc.element.antd.Transfer.propTypes.onChange)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>operations ()](#apidoc.element.antd.Transfer.propTypes.operations)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>prefixCls ()](#apidoc.element.antd.Transfer.propTypes.prefixCls)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>render ()](#apidoc.element.antd.Transfer.propTypes.render)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>rowKey ()](#apidoc.element.antd.Transfer.propTypes.rowKey)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>searchPlaceholder ()](#apidoc.element.antd.Transfer.propTypes.searchPlaceholder)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>showSearch ()](#apidoc.element.antd.Transfer.propTypes.showSearch)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>targetKeys ()](#apidoc.element.antd.Transfer.propTypes.targetKeys)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>titles ()](#apidoc.element.antd.Transfer.propTypes.titles)

#### [module antd.Transfer.prototype](#apidoc.module.antd.Transfer.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Transfer.prototype.</span>getLocale ()](#apidoc.element.antd.Transfer.prototype.getLocale)

#### [module antd.Tree](#apidoc.module.antd.Tree)
1.  [function <span class="apidocSignatureSpan">antd.</span>Tree ()](#apidoc.element.antd.Tree.Tree)
1.  [function <span class="apidocSignatureSpan">antd.Tree.</span>TreeNode (props)](#apidoc.element.antd.Tree.TreeNode)
1.  object <span class="apidocSignatureSpan">antd.Tree.</span>defaultProps

#### [module antd.Tree.TreeNode](#apidoc.module.antd.Tree.TreeNode)
1.  [function <span class="apidocSignatureSpan">antd.Tree.</span>TreeNode (props)](#apidoc.element.antd.Tree.TreeNode.TreeNode)
1.  number <span class="apidocSignatureSpan">antd.Tree.TreeNode.</span>isTreeNode
1.  object <span class="apidocSignatureSpan">antd.Tree.TreeNode.</span>defaultProps
1.  object <span class="apidocSignatureSpan">antd.Tree.TreeNode.</span>propTypes

#### [module antd.Tree.TreeNode.prototype](#apidoc.module.antd.Tree.TreeNode.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>componentDidMount ()](#apidoc.element.antd.Tree.TreeNode.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onCheck ()](#apidoc.element.antd.Tree.TreeNode.prototype.onCheck)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onContextMenu (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onContextMenu)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragEnd (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragEnd)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragEnter (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragEnter)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragLeave (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragLeave)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragOver (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragOver)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragStart (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragStart)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDrop (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDrop)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onExpand ()](#apidoc.element.antd.Tree.TreeNode.prototype.onExpand)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onKeyDown (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onKeyDown)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onMouseEnter (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onMouseEnter)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onMouseLeave (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onMouseLeave)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onSelect ()](#apidoc.element.antd.Tree.TreeNode.prototype.onSelect)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>render ()](#apidoc.element.antd.Tree.TreeNode.prototype.render)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>renderCheckbox (props)](#apidoc.element.antd.Tree.TreeNode.prototype.renderCheckbox)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>renderChildren (props)](#apidoc.element.antd.Tree.TreeNode.prototype.renderChildren)
1.  [function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>renderSwitcher (props, expandedState)](#apidoc.element.antd.Tree.TreeNode.prototype.renderSwitcher)

#### [module antd.Tree.prototype](#apidoc.module.antd.Tree.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Tree.prototype.</span>render ()](#apidoc.element.antd.Tree.prototype.render)

#### [module antd.TreeSelect](#apidoc.module.antd.TreeSelect)
1.  [function <span class="apidocSignatureSpan">antd.</span>TreeSelect ()](#apidoc.element.antd.TreeSelect.TreeSelect)
1.  object <span class="apidocSignatureSpan">antd.TreeSelect.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.TreeSelect.</span>defaultProps

#### [module antd.TreeSelect.contextTypes](#apidoc.module.antd.TreeSelect.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.TreeSelect.contextTypes.</span>antLocale ()](#apidoc.element.antd.TreeSelect.contextTypes.antLocale)

#### [module antd.TreeSelect.prototype](#apidoc.module.antd.TreeSelect.prototype)
1.  [function <span class="apidocSignatureSpan">antd.TreeSelect.prototype.</span>getLocale ()](#apidoc.element.antd.TreeSelect.prototype.getLocale)

#### [module antd.Upload](#apidoc.module.antd.Upload)
1.  [function <span class="apidocSignatureSpan">antd.</span>Upload (props)](#apidoc.element.antd.Upload.Upload)
1.  [function <span class="apidocSignatureSpan">antd.Upload.</span>Dragger ()](#apidoc.element.antd.Upload.Dragger)
1.  object <span class="apidocSignatureSpan">antd.Upload.</span>contextTypes
1.  object <span class="apidocSignatureSpan">antd.Upload.</span>defaultProps

#### [module antd.Upload.Dragger](#apidoc.module.antd.Upload.Dragger)
1.  [function <span class="apidocSignatureSpan">antd.Upload.</span>Dragger ()](#apidoc.element.antd.Upload.Dragger.Dragger)

#### [module antd.Upload.Dragger.prototype](#apidoc.module.antd.Upload.Dragger.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Upload.Dragger.prototype.</span>render ()](#apidoc.element.antd.Upload.Dragger.prototype.render)

#### [module antd.Upload.contextTypes](#apidoc.module.antd.Upload.contextTypes)
1.  [function <span class="apidocSignatureSpan">antd.Upload.contextTypes.</span>antLocale ()](#apidoc.element.antd.Upload.contextTypes.antLocale)

#### [module antd.Upload.defaultProps](#apidoc.module.antd.Upload.defaultProps)
1.  boolean <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>disabled
1.  boolean <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>multiple
1.  boolean <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>showUploadList
1.  boolean <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>supportServerRender
1.  [function <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>beforeUpload ()](#apidoc.element.antd.Upload.defaultProps.beforeUpload)
1.  object <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>data
1.  string <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>accept
1.  string <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>action
1.  string <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>className
1.  string <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>listType
1.  string <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>prefixCls
1.  string <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>type

#### [module antd.Upload.prototype](#apidoc.module.antd.Upload.prototype)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>autoUpdateProgress (_, file)](#apidoc.element.antd.Upload.prototype.autoUpdateProgress)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>clearProgressTimer ()](#apidoc.element.antd.Upload.prototype.clearProgressTimer)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Upload.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Upload.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>getLocale ()](#apidoc.element.antd.Upload.prototype.getLocale)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>handleRemove (file)](#apidoc.element.antd.Upload.prototype.handleRemove)
1.  [function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>render ()](#apidoc.element.antd.Upload.prototype.render)

#### [module antd.message](#apidoc.module.antd.message)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>config (options)](#apidoc.element.antd.message.config)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>destroy ()](#apidoc.element.antd.message.destroy)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>error (content, duration, onClose)](#apidoc.element.antd.message.error)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>info (content, duration, onClose)](#apidoc.element.antd.message.info)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>loading (content, duration, onClose)](#apidoc.element.antd.message.loading)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>success (content, duration, onClose)](#apidoc.element.antd.message.success)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>warn (content, duration, onClose)](#apidoc.element.antd.message.warn)
1.  [function <span class="apidocSignatureSpan">antd.message.</span>warning (content, duration, onClose)](#apidoc.element.antd.message.warning)

#### [module antd.notification](#apidoc.module.antd.notification)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>close (key)](#apidoc.element.antd.notification.close)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>config (options)](#apidoc.element.antd.notification.config)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>destroy ()](#apidoc.element.antd.notification.destroy)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>error (args)](#apidoc.element.antd.notification.error)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>info (args)](#apidoc.element.antd.notification.info)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>open (args)](#apidoc.element.antd.notification.open)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>success (args)](#apidoc.element.antd.notification.success)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>warn (args)](#apidoc.element.antd.notification.warn)
1.  [function <span class="apidocSignatureSpan">antd.notification.</span>warning (args)](#apidoc.element.antd.notification.warning)



# <a name="apidoc.module.antd"></a>[module antd](#apidoc.module.antd)

#### <a name="apidoc.element.antd.Affix"></a>[function <span class="apidocSignatureSpan">antd.</span>Affix (props)](#apidoc.element.antd.Affix)
- description and source-code
```javascript
function Affix(props) {
    (0, _classCallCheck3["default"])(this, Affix);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.state = {
        affixStyle: null,
        placeholderStyle: null
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Alert"></a>[function <span class="apidocSignatureSpan">antd.</span>Alert (props)](#apidoc.element.antd.Alert)
- description and source-code
```javascript
function Alert(props) {
    (0, _classCallCheck3["default"])(this, Alert);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleClose = function (e) {
        e.preventDefault();
        var dom = _reactDom2["default"].findDOMNode(_this);
        dom.style.height = dom.offsetHeight + 'px';
        // Magic code
        // 重复一次后才能正确设置 height
        dom.style.height = dom.offsetHeight + 'px';
        _this.setState({
            closing: false
        });
        (_this.props.onClose || noop)(e);
    };
    _this.animationEnd = function () {
        _this.setState({
            closed: true,
            closing: true
        });
    };
    _this.state = {
        closing: true,
        closed: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor"></a>[function <span class="apidocSignatureSpan">antd.</span>Anchor (props)](#apidoc.element.antd.Anchor)
- description and source-code
```javascript
function Anchor(props) {
    (0, _classCallCheck3["default"])(this, Anchor);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleScroll = function () {
        _this.setState({
            activeAnchor: _this.anchorHelper.getCurrentAnchor(_this.props.offsetTop, _this.props.bounds)
        });
    };
    _this.updateInk = function () {
        var activeAnchor = _this.anchorHelper.getCurrentActiveAnchor();
        if (activeAnchor) {
            _this.refs.ink.style.top = activeAnchor.offsetTop + activeAnchor.clientHeight / 2 - 4.5 + 'px';
        }
    };
    _this.clickAnchorLink = function (href, component) {
        _this._avoidInk = true;
        _this.refs.ink.style.top = component.offsetTop + component.clientHeight / 2 - 4.5 + 'px';
        _this.anchorHelper.scrollTo(href, _this.props.offsetTop, _anchorHelper.getDefaultTarget, function () {
            _this._avoidInk = false;
        });
    };
    _this.renderAnchorLink = function (child) {
        var href = child.props.href;

        if (child.type.__ANT_ANCHOR_LINK && href) {
            _this.anchorHelper.addLink(href);
            return _react2["default"].cloneElement(child, {
                onClick: _this.clickAnchorLink,
                prefixCls: _this.props.prefixCls,
                bounds: _this.props.bounds,
                affix: _this.props.affix || _this.props.showInkInFixed,
                offsetTop: _this.props.offsetTop
            });
        }
        return child;
    };
    _this.state = {
        activeAnchor: null,
        animated: true
    };
    _this.anchorHelper = new _anchorHelper2["default"]();
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.Link"></a>[function <span class="apidocSignatureSpan">antd.</span>Anchor.Link ()](#apidoc.element.antd.Anchor.Link)
- description and source-code
```javascript
function AnchorLink() {
    (0, _classCallCheck3["default"])(this, AnchorLink);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.renderAnchorLink = function (child) {
        var href = child.props.href;

        if (href) {
            _this.context.anchorHelper.addLink(href);
            return _react2["default"].cloneElement(child, {
                onClick: _this.props.onClick,
                prefixCls: _this.props.prefixCls,
                affix: _this.props.affix,
                offsetTop: _this.props.offsetTop
            });
        }
        return child;
    };
    _this.refsTo = function (component) {
        _this._component = component;
    };
    _this.scrollTo = function (e) {
        e.preventDefault();
        var _this$props = _this.props,
            onClick = _this$props.onClick,
            href = _this$props.href;
        var anchorHelper = _this.context.anchorHelper;

        if (onClick) {
            onClick(href, _this._component);
        } else {
            var scrollToFn = anchorHelper ? anchorHelper.scrollTo : _anchorHelper.scrollTo;
            scrollToFn(href, _this.props.offsetTop);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.AutoComplete"></a>[function <span class="apidocSignatureSpan">antd.</span>AutoComplete ()](#apidoc.element.antd.AutoComplete)
- description and source-code
```javascript
function AutoComplete() {
    (0, _classCallCheck3["default"])(this, AutoComplete);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.getInputElement = function () {
        var children = _this.props.children;

        var element = children && _react2["default"].isValidElement(children) && children.type !== _rcSelect.Option ? _react2["default
"].Children.only(_this.props.children) : _react2["default"].createElement(_input2["default"], null);
        return _react2["default"].createElement(
            _InputElement2["default"],
            { className: 'ant-input' },
            element
        );
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.BackTop"></a>[function <span class="apidocSignatureSpan">antd.</span>BackTop (props)](#apidoc.element.antd.BackTop)
- description and source-code
```javascript
function BackTop(props) {
    (0, _classCallCheck3["default"])(this, BackTop);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.getCurrentScrollTop = function () {
        var targetNode = (_this.props.target || getDefaultTarget)();
        if (targetNode === window) {
            return window.pageYOffset || document.body.scrollTop || document.documentElement.scrollTop;
        }
        return targetNode.scrollTop;
    };
    _this.scrollToTop = function (e) {
        var scrollTop = _this.getCurrentScrollTop();
        var startTime = Date.now();
        var frameFunc = function frameFunc() {
            var timestamp = Date.now();
            var time = timestamp - startTime;
            _this.setScrollTop(easeInOutCubic(time, scrollTop, 0, 450));
            if (time < 450) {
                reqAnimFrame(frameFunc);
            }
        };
        reqAnimFrame(frameFunc);
        (_this.props.onClick || noop)(e);
    };
    _this.handleScroll = function () {
        var _this$props = _this.props,
            visibilityHeight = _this$props.visibilityHeight,
            _this$props$target = _this$props.target,
            target = _this$props$target === undefined ? getDefaultTarget : _this$props$target;

        var scrollTop = (0, _getScroll2["default"])(target(), true);
        _this.setState({
            visible: scrollTop > visibilityHeight
        });
    };
    _this.state = {
        visible: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Badge"></a>[function <span class="apidocSignatureSpan">antd.</span>Badge ()](#apidoc.element.antd.Badge)
- description and source-code
```javascript
function Badge() {
    (0, _classCallCheck3["default"])(this, Badge);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb"></a>[function <span class="apidocSignatureSpan">antd.</span>Breadcrumb ()](#apidoc.element.antd.Breadcrumb)
- description and source-code
```javascript
function Breadcrumb() {
    (0, _classCallCheck3["default"])(this, Breadcrumb);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.Item"></a>[function <span class="apidocSignatureSpan">antd.</span>Breadcrumb.Item ()](#apidoc.element.antd.Breadcrumb.Item)
- description and source-code
```javascript
function BreadcrumbItem() {
    (0, _classCallCheck3["default"])(this, BreadcrumbItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button"></a>[function <span class="apidocSignatureSpan">antd.</span>Button (props)](#apidoc.element.antd.Button)
- description and source-code
```javascript
function Button(props) {
    (0, _classCallCheck3["default"])(this, Button);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleClick = function (e) {
        // Add click effect
        _this.setState({ clicked: true });
        clearTimeout(_this.timeout);
        _this.timeout = setTimeout(function () {
            return _this.setState({ clicked: false });
        }, 500);
        var onClick = _this.props.onClick;
        if (onClick) {
            onClick(e);
        }
    };
    // Handle auto focus when click button in Chrome
    _this.handleMouseUp = function (e) {
        (0, _reactDom.findDOMNode)(_this).blur();
        if (_this.props.onMouseUp) {
            _this.props.onMouseUp(e);
        }
    };
    _this.state = {
        loading: props.loading
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar"></a>[function <span class="apidocSignatureSpan">antd.</span>Calendar (props, context)](#apidoc.element.antd.Calendar)
- description and source-code
```javascript
function Calendar(props, context) {
    (0, _classCallCheck3["default"])(this, Calendar);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props, context));

    _this.monthCellRender = function (value) {
        var _this$props = _this.props,
            prefixCls = _this$props.prefixCls,
            _this$props$monthCell = _this$props.monthCellRender,
            monthCellRender = _this$props$monthCell === undefined ? noop : _this$props$monthCell;

        return _react2["default"].createElement(
            'div',
            { className: prefixCls + '-month' },
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-value' },
                value.localeData().monthsShort(value)
            ),
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-content' },
                monthCellRender(value)
            )
        );
    };
    _this.dateCellRender = function (value) {
        var _this$props2 = _this.props,
            prefixCls = _this$props2.prefixCls,
            _this$props2$dateCell = _this$props2.dateCellRender,
            dateCellRender = _this$props2$dateCell === undefined ? noop : _this$props2$dateCell;

        return _react2["default"].createElement(
            'div',
            { className: prefixCls + '-date' },
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-value' },
                zerofixed(value.date())
            ),
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-content' },
                dateCellRender(value)
            )
        );
    };
    _this.setValue = function (value, way) {
        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        if (way === 'select') {
            if (_this.props.onSelect) {
                _this.props.onSelect(value);
            }
        } else if (way === 'changePanel') {
            _this.onPanelChange(value, _this.state.mode);
        }
    };
    _this.setType = function (type) {
        var mode = type === 'date' ? 'month' : 'year';
        if (_this.state.mode !== mode) {
            _this.setState({ mode: mode });
            _this.onPanelChange(_this.state.value, mode);
        }
    };
    _this.onHeaderValueChange = function (value) {
        _this.setValue(value, 'changePanel');
    };
    _this.onHeaderTypeChange = function (type) {
        _this.setType(type);
    };
    _this.onSelect = function (value) {
        _this.setValue(value, 'select');
    };
    // Make sure that moment locale had be set correctly.
    (0, _getLocale.getComponentLocale)(props, context, 'Calendar', function () {
        return require('./locale/zh_CN');
    });
    var value = props.value || props.defaultValue || (0, _moment2["default"])();
    if (!_moment2["default"].isMoment(value)) {
        throw new Error('The value/defaultValue of Calendar must be a moment object after 'antd@2.0', ' + 'see: http://u.ant.design
/calendar-value');
    }
    _this.state = {
        value: value,
        mode: props.mode
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Card"></a>[function <span class="apidocSignatureSpan">antd.</span>Card (props)](#apidoc.element.antd.Card)
- description and source-code
```javascript
Card = function (props) {
  var _classNames;

  var _props$prefixCls = props.prefixCls,
      prefixCls = _props$prefixCls === undefined ? 'ant-card' : _props$prefixCls,
      className = props.className,
      extra = props.extra,
      bodyStyle = props.bodyStyle,
      title = props.title,
      loading = props.loading,
      _props$bordered = props.bordered,
      bordered = _props$bordered === undefined ? true : _props$bordered,
      others = __rest(props, ["prefixCls", "className", "extra", "bodyStyle", "title", "loading", "bordered"]);

  var children = props.children;
  var classString = (0, _classnames2["default"])(prefixCls, className, (_classNames = {}, (0, _defineProperty3["default"])(_classNames
, prefixCls + '-loading', loading), (0, _defineProperty3["default"])(_classNames, prefixCls + '-bordered', bordered), _classNames
));
  if (loading) {
    children = _react2["default"].createElement(
      'div',
      null,
      _react2["default"].createElement('p', { className: prefixCls + '-loading-block', style: { width: '94%' } }),
      _react2["default"].createElement(
        'p',
        null,
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '28%' } }),
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '62%' } })
      ),
      _react2["default"].createElement(
        'p',
        null,
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '22%' } }),
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '66%' } })
      ),
      _react2["default"].createElement(
        'p',
        null,
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '56%' } }),
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '39%' } })
      ),
      _react2["default"].createElement(
        'p',
        null,
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '21%' } }),
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '15%' } }),
        _react2["default"].createElement('span', { className: prefixCls + '-loading-block', style: { width: '40%' } })
      )
    );
  }
  var head = void 0;
  if (!title) {
    head = null;
  } else {
    head = typeof title === 'string' ? _react2["default"].createElement(
      'div',
      { className: prefixCls + '-head' },
      _react2["default"].createElement(
        'h3',
        { className: prefixCls + '-head-title' },
        title
      )
    ) : _react2["default"].createElement(
      'div',
      { className: prefixCls + '-head' },
      _react2["default"].createElement(
        'div',
        { className: prefixCls + '-head-title' },
        title
      )
    );
  }
  return _react2["default"].createElement(
    'div',
    (0, _extends3["default"])({}, others, { className: classString }),
    head,
    extra ? _react2["default"].createElement(
      'div',
      { className: prefixCls + '-extra' },
      extra
    ) : null,
    _react2["default"].createElement(
      'div',
      { className: prefixCls + '-body', style: bodyStyle },
      children
    )
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Carousel"></a>[function <span class="apidocSignatureSpan">antd.</span>Carousel ()](#apidoc.element.antd.Carousel)
- description and source-code
```javascript
function Carousel() {
    (0, _classCallCheck3["default"])(this, Carousel);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this));

    _this.onWindowResized = function () {
        // Fix https://github.com/ant-design/ant-design/issues/2550
        var slick = _this.refs.slick;
        var autoplay = _this.props.autoplay;

        if (autoplay && slick && slick.innerSlider && slick.innerSlider.autoPlay) {
            slick.innerSlider.autoPlay();
        }
    };
    _this.onWindowResized = (0, _lodash2["default"])(_this.onWindowResized, 500, {
        leading: false
    });
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Cascader"></a>[function <span class="apidocSignatureSpan">antd.</span>Cascader (props)](#apidoc.element.antd.Cascader)
- description and source-code
```javascript
function Cascader(props) {
    (0, _classCallCheck3["default"])(this, Cascader);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleChange = function (value, selectedOptions) {
        _this.setState({ inputValue: '' });
        if (selectedOptions[0].__IS_FILTERED_OPTION) {
            var unwrappedValue = value[0];
            var unwrappedSelectedOptions = selectedOptions[0].path;
            _this.setValue(unwrappedValue, unwrappedSelectedOptions);
            return;
        }
        _this.setValue(value, selectedOptions);
    };
    _this.handlePopupVisibleChange = function (popupVisible) {
        _this.setState({
            popupVisible: popupVisible,
            inputFocused: popupVisible,
            inputValue: popupVisible ? _this.state.inputValue : ''
        });
        var onPopupVisibleChange = _this.props.onPopupVisibleChange;
        if (onPopupVisibleChange) {
            onPopupVisibleChange(popupVisible);
        }
    };
    _this.handleInputBlur = function () {
        _this.setState({
            inputFocused: false
        });
    };
    _this.handleInputClick = function (e) {
        var _this$state = _this.state,
            inputFocused = _this$state.inputFocused,
            popupVisible = _this$state.popupVisible;
        // Prevent 'Trigger' behaviour.

        if (inputFocused || popupVisible) {
            e.stopPropagation();
            e.nativeEvent.stopImmediatePropagation();
        }
    };
    _this.handleKeyDown = function (e) {
        if (e.keyCode === _KeyCode2["default"].BACKSPACE) {
            e.stopPropagation();
        }
    };
    _this.handleInputChange = function (e) {
        var inputValue = e.target.value;
        _this.setState({ inputValue: inputValue });
    };
    _this.setValue = function (value) {
        var selectedOptions = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : [];

        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(value, selectedOptions);
        }
    };
    _this.clearSelection = function (e) {
        e.preventDefault();
        e.stopPropagation();
        if (!_this.state.inputValue) {
            _this.setValue([]);
            _this.setState({ popupVisible: false });
        } else {
            _this.setState({ inputValue: '' });
        }
    };
    _this.state = {
        value: props.value || props.defaultValue || [],
        inputValue: '',
        inputFocused: false,
        popupVisible: false,
        flattenOptions: props.showSearch && _this.flattenTree(props.options, props.changeOnSelect)
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Checkbox"></a>[function <span class="apidocSignatureSpan">antd.</span>Checkbox ()](#apidoc.element.antd.Checkbox)
- description and source-code
```javascript
function Checkbox() {
    (0, _classCallCheck3["default"])(this, Checkbox);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Checkbox.Group"></a>[function <span class="apidocSignatureSpan">antd.</span>Checkbox.Group (props)](#apidoc.element.antd.Checkbox.Group)
- description and source-code
```javascript
function CheckboxGroup(props) {
    (0, _classCallCheck3["default"])(this, CheckboxGroup);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.toggleOption = function (option) {
        var optionIndex = _this.state.value.indexOf(option.value);
        var value = [].concat((0, _toConsumableArray3["default"])(_this.state.value));
        if (optionIndex === -1) {
            value.push(option.value);
        } else {
            value.splice(optionIndex, 1);
        }
        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(value);
        }
    };
    _this.state = {
        value: props.value || props.defaultValue || []
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col"></a>[function <span class="apidocSignatureSpan">antd.</span>Col ()](#apidoc.element.antd.Col)
- description and source-code
```javascript
function Col() {
    (0, _classCallCheck3["default"])(this, Col);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse"></a>[function <span class="apidocSignatureSpan">antd.</span>Collapse ()](#apidoc.element.antd.Collapse)
- description and source-code
```javascript
function Collapse() {
    (0, _classCallCheck3["default"])(this, Collapse);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component2.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel"></a>[function <span class="apidocSignatureSpan">antd.</span>Collapse.Panel (props, context, updater)](#apidoc.element.antd.Collapse.Panel)
- description and source-code
```javascript
Collapse.Panel = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker"></a>[function <span class="apidocSignatureSpan">antd.</span>DatePicker (props, context, updater)](#apidoc.element.antd.DatePicker)
- description and source-code
```javascript
DatePicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.Calendar"></a>[function <span class="apidocSignatureSpan">antd.</span>DatePicker.Calendar ()](#apidoc.element.antd.DatePicker.Calendar)
- description and source-code
```javascript
function Calendar() {
    (0, _classCallCheck3["default"])(this, Calendar);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker"></a>[function <span class="apidocSignatureSpan">antd.</span>DatePicker.MonthPicker (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker)
- description and source-code
```javascript
DatePicker.MonthPicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker"></a>[function <span class="apidocSignatureSpan">antd.</span>DatePicker.RangePicker (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker)
- description and source-code
```javascript
DatePicker.RangePicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Dropdown"></a>[function <span class="apidocSignatureSpan">antd.</span>Dropdown ()](#apidoc.element.antd.Dropdown)
- description and source-code
```javascript
function Dropdown() {
    (0, _classCallCheck3["default"])(this, Dropdown);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Dropdown.Button"></a>[function <span class="apidocSignatureSpan">antd.</span>Dropdown.Button ()](#apidoc.element.antd.Dropdown.Button)
- description and source-code
```javascript
function DropdownButton() {
    (0, _classCallCheck3["default"])(this, DropdownButton);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form"></a>[function <span class="apidocSignatureSpan">antd.</span>Form (props)](#apidoc.element.antd.Form)
- description and source-code
```javascript
function Form(props) {
    (0, _classCallCheck3["default"])(this, Form);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    (0, _warning2["default"])(!props.form, 'It is unnecessary to pass 'form' to 'Form' after antd@1.7.0.');
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item"></a>[function <span class="apidocSignatureSpan">antd.</span>Form.Item ()](#apidoc.element.antd.Form.Item)
- description and source-code
```javascript
function FormItem() {
    (0, _classCallCheck3["default"])(this, FormItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Icon"></a>[function <span class="apidocSignatureSpan">antd.</span>Icon (props)](#apidoc.element.antd.Icon)
- description and source-code
```javascript
Icon = function (props) {
    var type = props.type,
        _props$className = props.className,
        className = _props$className === undefined ? '' : _props$className,
        spin = props.spin;

    var classString = (0, _classnames2["default"])((0, _defineProperty3["default"])({
        anticon: true,
        'anticon-spin': !!spin || type === 'loading'
    }, 'anticon-' + type, true), className);
    return React.createElement('i', (0, _extends3["default"])({}, (0, _omit2["default"])(props, ['type', 'spin']), { className:
classString }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input"></a>[function <span class="apidocSignatureSpan">antd.</span>Input ()](#apidoc.element.antd.Input)
- description and source-code
```javascript
function Input() {
    (0, _classCallCheck3["default"])(this, Input);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));

    _this.state = {
        textareaStyles: null,
        isFocus: false
    };
    _this.handleKeyDown = function (e) {
        var _this$props = _this.props,
            onPressEnter = _this$props.onPressEnter,
            onKeyDown = _this$props.onKeyDown;

        if (e.keyCode === 13 && onPressEnter) {
            onPressEnter(e);
        }
        if (onKeyDown) {
            onKeyDown(e);
        }
    };
    _this.handleTextareaChange = function (e) {
        if (!('value' in _this.props)) {
            _this.resizeTextarea();
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(e);
        }
    };
    _this.resizeTextarea = function () {
        var _this$props2 = _this.props,
            type = _this$props2.type,
            autosize = _this$props2.autosize;

        if (type !== 'textarea' || !autosize || !_this.refs.input) {
            return;
        }
        var minRows = autosize ? autosize.minRows : null;
        var maxRows = autosize ? autosize.maxRows : null;
        var textareaStyles = (0, _calculateNodeHeight2["default"])(_this.refs.input, false, minRows, maxRows);
        _this.setState({ textareaStyles: textareaStyles });
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.Search"></a>[function <span class="apidocSignatureSpan">antd.</span>Input.Search ()](#apidoc.element.antd.Input.Search)
- description and source-code
```javascript
function Search() {
    (0, _classCallCheck3["default"])(this, Search);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.onSearch = function () {
        var onSearch = _this.props.onSearch;

        if (onSearch) {
            onSearch(_this.input.refs.input.value);
        }
        _this.input.refs.input.focus();
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.InputNumber"></a>[function <span class="apidocSignatureSpan">antd.</span>InputNumber ()](#apidoc.element.antd.InputNumber)
- description and source-code
```javascript
function InputNumber() {
    (0, _classCallCheck3["default"])(this, InputNumber);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout"></a>[function <span class="apidocSignatureSpan">antd.</span>Layout ()](#apidoc.element.antd.Layout)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Content"></a>[function <span class="apidocSignatureSpan">antd.</span>Layout.Content ()](#apidoc.element.antd.Layout.Content)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Footer"></a>[function <span class="apidocSignatureSpan">antd.</span>Layout.Footer ()](#apidoc.element.antd.Layout.Footer)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Header"></a>[function <span class="apidocSignatureSpan">antd.</span>Layout.Header ()](#apidoc.element.antd.Layout.Header)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Sider"></a>[function <span class="apidocSignatureSpan">antd.</span>Layout.Sider (props)](#apidoc.element.antd.Layout.Sider)
- description and source-code
```javascript
function Sider(props) {
    (0, _classCallCheck3["default"])(this, Sider);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.responsiveHandler = function (mql) {
        _this.setState({ below: mql.matches });
        if (_this.state.collapsed !== mql.matches) {
            _this.setCollapsed(mql.matches, 'responsive');
        }
    };
    _this.setCollapsed = function (collapsed, type) {
        if (!('collapsed' in _this.props)) {
            _this.setState({
                collapsed: collapsed
            });
        }
        var onCollapse = _this.props.onCollapse;

        if (onCollapse) {
            onCollapse(collapsed, type);
        }
    };
    _this.toggle = function () {
        var collapsed = !_this.state.collapsed;
        _this.setCollapsed(collapsed, 'clickTrigger');
    };
    _this.belowShowChange = function () {
        _this.setState({ belowShow: !_this.state.belowShow });
    };
    var matchMedia = void 0;
    if (typeof window !== 'undefined') {
        matchMedia = window.matchMedia;
    }
    if (matchMedia && props.breakpoint && props.breakpoint in dimensionMap) {
        _this.mql = matchMedia('(max-width: ' + dimensionMap[props.breakpoint] + ')');
    }
    var collapsed = void 0;
    if ('collapsed' in props) {
        collapsed = props.collapsed;
    } else {
        collapsed = props.defaultCollapsed;
    }
    _this.state = {
        collapsed: collapsed,
        below: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.LocaleProvider"></a>[function <span class="apidocSignatureSpan">antd.</span>LocaleProvider ()](#apidoc.element.antd.LocaleProvider)
- description and source-code
```javascript
function LocaleProvider() {
    (0, _classCallCheck3["default"])(this, LocaleProvider);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention"></a>[function <span class="apidocSignatureSpan">antd.</span>Mention {{signature}}](#apidoc.element.antd.Mention)
- description and source-code
```javascript
n/a
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.Nav"></a>[function <span class="apidocSignatureSpan">antd.</span>Mention.Nav ()](#apidoc.element.antd.Mention.Nav)
- description and source-code
```javascript
function Nav() {
  _classCallCheck(this, Nav);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu"></a>[function <span class="apidocSignatureSpan">antd.</span>Menu (props)](#apidoc.element.antd.Menu)
- description and source-code
```javascript
function Menu(props) {
    (0, _classCallCheck3["default"])(this, Menu);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleClick = function (e) {
        _this.setOpenKeys([]);
        var onClick = _this.props.onClick;

        if (onClick) {
            onClick(e);
        }
    };
    _this.handleOpenChange = function (openKeys) {
        _this.setOpenKeys(openKeys);
        var onOpenChange = _this.props.onOpenChange;

        if (onOpenChange) {
            onOpenChange(openKeys);
        }
    };
    (0, _warning2["default"])(!('onOpen' in props || 'onClose' in props), ''onOpen' and 'onClose' are removed, please use 'onOpenChange
' instead, ' + 'see: http://u.ant.design/menu-on-open-change.');
    var openKeys = void 0;
    if ('defaultOpenKeys' in props) {
        openKeys = props.defaultOpenKeys;
    } else if ('openKeys' in props) {
        openKeys = props.openKeys;
    }
    _this.state = {
        openKeys: openKeys || []
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Divider"></a>[function <span class="apidocSignatureSpan">antd.</span>Menu.Divider (props, context, updater)](#apidoc.element.antd.Menu.Divider)
- description and source-code
```javascript
Menu.Divider = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item"></a>[function <span class="apidocSignatureSpan">antd.</span>Menu.Item (props, context, updater)](#apidoc.element.antd.Menu.Item)
- description and source-code
```javascript
Menu.Item = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.ItemGroup"></a>[function <span class="apidocSignatureSpan">antd.</span>Menu.ItemGroup (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup)
- description and source-code
```javascript
Menu.ItemGroup = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu"></a>[function <span class="apidocSignatureSpan">antd.</span>Menu.SubMenu (props, context, updater)](#apidoc.element.antd.Menu.SubMenu)
- description and source-code
```javascript
Menu.SubMenu = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal"></a>[function <span class="apidocSignatureSpan">antd.</span>Modal ()](#apidoc.element.antd.Modal)
- description and source-code
```javascript
function Modal() {
    (0, _classCallCheck3["default"])(this, Modal);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.handleCancel = function (e) {
        var onCancel = _this.props.onCancel;
        if (onCancel) {
            onCancel(e);
        }
    };
    _this.handleOk = function (e) {
        var onOk = _this.props.onOk;
        if (onOk) {
            onOk(e);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Pagination"></a>[function <span class="apidocSignatureSpan">antd.</span>Pagination ()](#apidoc.element.antd.Pagination)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Popconfirm"></a>[function <span class="apidocSignatureSpan">antd.</span>Popconfirm ()](#apidoc.element.antd.Popconfirm)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Popover"></a>[function <span class="apidocSignatureSpan">antd.</span>Popover ()](#apidoc.element.antd.Popover)
- description and source-code
```javascript
function Popover() {
    (0, _classCallCheck3["default"])(this, Popover);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress"></a>[function <span class="apidocSignatureSpan">antd.</span>Progress ()](#apidoc.element.antd.Progress)
- description and source-code
```javascript
function Progress() {
    (0, _classCallCheck3["default"])(this, Progress);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio"></a>[function <span class="apidocSignatureSpan">antd.</span>Radio ()](#apidoc.element.antd.Radio)
- description and source-code
```javascript
function Radio() {
    (0, _classCallCheck3["default"])(this, Radio);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio.Button"></a>[function <span class="apidocSignatureSpan">antd.</span>Radio.Button ()](#apidoc.element.antd.Radio.Button)
- description and source-code
```javascript
function RadioButton() {
    (0, _classCallCheck3["default"])(this, RadioButton);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio.Group"></a>[function <span class="apidocSignatureSpan">antd.</span>Radio.Group (props)](#apidoc.element.antd.Radio.Group)
- description and source-code
```javascript
function RadioGroup(props) {
    (0, _classCallCheck3["default"])(this, RadioGroup);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onRadioChange = function (ev) {
        var lastValue = _this.state.value;
        var value = ev.target.value;

        if (!('value' in _this.props)) {
            _this.setState({
                value: value
            });
        }
        var onChange = _this.props.onChange;
        if (onChange && value !== lastValue) {
            onChange(ev);
        }
    };
    var value = void 0;
    if ('value' in props) {
        value = props.value;
    } else if ('defaultValue' in props) {
        value = props.defaultValue;
    } else {
        var checkedValue = getCheckedValue(props.children);
        value = checkedValue && checkedValue.value;
    }
    _this.state = {
        value: value
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Rate"></a>[function <span class="apidocSignatureSpan">antd.</span>Rate ()](#apidoc.element.antd.Rate)
- description and source-code
```javascript
function Rate() {
    (0, _classCallCheck3["default"])(this, Rate);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row"></a>[function <span class="apidocSignatureSpan">antd.</span>Row ()](#apidoc.element.antd.Row)
- description and source-code
```javascript
function Row() {
    (0, _classCallCheck3["default"])(this, Row);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select"></a>[function <span class="apidocSignatureSpan">antd.</span>Select ()](#apidoc.element.antd.Select)
- description and source-code
```javascript
function Select() {
    (0, _classCallCheck3["default"])(this, Select);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Slider"></a>[function <span class="apidocSignatureSpan">antd.</span>Slider (props)](#apidoc.element.antd.Slider)
- description and source-code
```javascript
function Slider(props) {
    (0, _classCallCheck3["default"])(this, Slider);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.toggleTooltipVisible = function (index, visible) {
        _this.setState(function (_ref) {
            var visibles = _ref.visibles;
            return {
                visibles: (0, _extends4["default"])({}, visibles, (0, _defineProperty3["default"])({}, index, visible))
            };
        });
    };
    _this.handleWithTooltip = function (_a) {
        var value = _a.value,
            dragging = _a.dragging,
            index = _a.index,
            restProps = __rest(_a, ["value", "dragging", "index"]);

        var _this$props = _this.props,
            tooltipPrefixCls = _this$props.tooltipPrefixCls,
            tipFormatter = _this$props.tipFormatter;
        var visibles = _this.state.visibles;

        return _react2["default"].createElement(
            _tooltip2["default"],
            { prefixCls: tooltipPrefixCls, title: tipFormatter ? tipFormatter(value) : '', visible: tipFormatter && (visibles[index
] || dragging), placement: 'top', transitionName: 'zoom-down', key: index },
            _react2["default"].createElement(_Handle2["default"], (0, _extends4["default"])({}, restProps, { onMouseEnter: function
 onMouseEnter() {
                    return _this.toggleTooltipVisible(index, true);
                }, onMouseLeave: function onMouseLeave() {
                    return _this.toggleTooltipVisible(index, false);
                } }))
        );
    };
    _this.state = {
        visibles: {}
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin"></a>[function <span class="apidocSignatureSpan">antd.</span>Spin (props)](#apidoc.element.antd.Spin)
- description and source-code
```javascript
function Spin(props) {
    (0, _classCallCheck3["default"])(this, Spin);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    var spinning = props.spinning;
    _this.state = {
        spinning: spinning
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Steps"></a>[function <span class="apidocSignatureSpan">antd.</span>Steps ()](#apidoc.element.antd.Steps)
- description and source-code
```javascript
function Steps() {
    (0, _classCallCheck3["default"])(this, Steps);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Steps.Step"></a>[function <span class="apidocSignatureSpan">antd.</span>Steps.Step ()](#apidoc.element.antd.Steps.Step)
- description and source-code
```javascript
function Step() {
  _classCallCheck(this, Step);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Switch"></a>[function <span class="apidocSignatureSpan">antd.</span>Switch ()](#apidoc.element.antd.Switch)
- description and source-code
```javascript
function Switch() {
    (0, _classCallCheck3["default"])(this, Switch);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table"></a>[function <span class="apidocSignatureSpan">antd.</span>Table (props)](#apidoc.element.antd.Table)
- description and source-code
```javascript
function Table(props) {
    (0, _classCallCheck3["default"])(this, Table);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.getCheckboxPropsByItem = function (item, index) {
        var _this$props$rowSelect = _this.props.rowSelection,
            rowSelection = _this$props$rowSelect === undefined ? {} : _this$props$rowSelect;

        if (!rowSelection.getCheckboxProps) {
            return {};
        }
        var key = _this.getRecordKey(item, index);
        // Cache checkboxProps
        if (!_this.CheckboxPropsCache[key]) {
            _this.CheckboxPropsCache[key] = rowSelection.getCheckboxProps(item);
        }
        return _this.CheckboxPropsCache[key];
    };
    _this.handleFilter = function (column, nextFilters) {
        var props = _this.props;
        var pagination = (0, _objectAssign2["default"])({}, _this.state.pagination);
        var filters = (0, _objectAssign2["default"])({}, _this.state.filters, (0, _defineProperty3["default"])({}, _this.getColumnKey
(column), nextFilters));
        // Remove filters not in current columns
        var currentColumnKeys = [];
        (0, _util.treeMap)(_this.columns, function (c) {
            if (!c.children) {
                currentColumnKeys.push(_this.getColumnKey(c));
            }
        });
        Object.keys(filters).forEach(function (columnKey) {
            if (currentColumnKeys.indexOf(columnKey) < 0) {
                delete filters[columnKey];
            }
        });
        if (props.pagination) {
            // Reset current prop
            pagination.current = 1;
            pagination.onChange(pagination.current);
        }
        var newState = {
            pagination: pagination,
            filters: {}
        };
        var filtersToSetState = (0, _objectAssign2["default"])({}, filters);
        // Remove filters which is controlled
        _this.getFilteredValueColumns().forEach(function (col) {
            var columnKey = _this.getColumnKey(col);
            if (columnKey) {
                delete filtersToSetState[columnKey];
            }
        });
        if (Object.keys(filtersToSetState).length > 0) {
            newState.filters = filtersToSetState;
        }
        // Controlled current prop will not respond user interaction
        if ((0, _typeof3["default"])(props.pagination) === 'object' && 'current' in props.pagination) {
            newState.pagination = (0, _objectAssign2["default"])({}, pagination, {
                current: _this.state.pagination.current
            });
        }
        _this.setState(newState, function () {
            _this.store.setState({
                selectionDirty: false
            });
            var onChange = _this.props.onChange;
            if (onChange) {
                onChange.apply(null, _this.prepareParamsArguments((0, _objectAssign2["default"])({}, _this.state, {
                    selectionDirty: false,
                    filters: filters,
                    pagination: pagination
                })));
            }
        });
    };
    _this.handleSelect = function (record, rowIndex, e) {
        var checked = e.target.checked;
        var defaultSelection = _this.store.getState().selectionDirty ? [] : _this.getDefaultSelection();
        var selectedRowKeys = _this.store.getState().selectedRowKeys.concat(defaultSelection);
        var key = _this.getRecordKey(record, rowIndex);
        if (checked) {
            selectedRowKeys.push(_this.getRecordKey(record, rowIndex));
        } else {
            selectedRowKeys = selectedRowKeys.filter(function (i) {
                return key !== i;
            });
        }
        _this.store.setState({
            selectionDirty: true
        });
        _this.setSelectedRowKeys(selectedRowKeys, {
            selectWay: 'onSelect',
            record: record,
            checked: checked
        });
    };
    _this.handleRadioSelect = function (record, rowIndex, e) {
        var checked = e.target.checked;
        var defaultSelection = _this.store.getState(). ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs"></a>[function <span class="apidocSignatureSpan">antd.</span>Tabs ()](#apidoc.element.antd.Tabs)
- description and source-code
```javascript
function Tabs() {
    (0, _classCallCheck3["default"])(this, Tabs);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.createNewTab = function (targetKey) {
        var onEdit = _this.props.onEdit;
        if (onEdit) {
            onEdit(targetKey, 'add');
        }
    };
    _this.removeTab = function (targetKey, e) {
        e.stopPropagation();
        if (!targetKey) {
            return;
        }
        var onEdit = _this.props.onEdit;
        if (onEdit) {
            onEdit(targetKey, 'remove');
        }
    };
    _this.handleChange = function (activeKey) {
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(activeKey);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs.TabPane"></a>[function <span class="apidocSignatureSpan">antd.</span>Tabs.TabPane (props, context, updater)](#apidoc.element.antd.Tabs.TabPane)
- description and source-code
```javascript
Tabs.TabPane = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tag"></a>[function <span class="apidocSignatureSpan">antd.</span>Tag (props)](#apidoc.element.antd.Tag)
- description and source-code
```javascript
function Tag(props) {
    (0, _classCallCheck3["default"])(this, Tag);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.close = function (e) {
        var onClose = _this.props.onClose;
        if (onClose) {
            onClose(e);
        }
        if (e.defaultPrevented) {
            return;
        }
        var dom = _reactDom2["default"].findDOMNode(_this);
        dom.style.width = dom.getBoundingClientRect().width + 'px';
        // It's Magic Code, don't know why
        dom.style.width = dom.getBoundingClientRect().width + 'px';
        _this.setState({
            closing: true
        });
    };
    _this.animationEnd = function (_, existed) {
        if (!existed && !_this.state.closed) {
            _this.setState({
                closed: true,
                closing: false
            });
            var afterClose = _this.props.afterClose;
            if (afterClose) {
                afterClose();
            }
        }
    };
    _this.state = {
        closing: false,
        closed: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tag.CheckableTag"></a>[function <span class="apidocSignatureSpan">antd.</span>Tag.CheckableTag ()](#apidoc.element.antd.Tag.CheckableTag)
- description and source-code
```javascript
function CheckableTag() {
    (0, _classCallCheck3["default"])(this, CheckableTag);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.handleClick = function () {
        var _this$props = _this.props,
            checked = _this$props.checked,
            onChange = _this$props.onChange;

        if (onChange) {
            onChange(!checked);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.TimePicker"></a>[function <span class="apidocSignatureSpan">antd.</span>TimePicker ()](#apidoc.element.antd.TimePicker)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Timeline"></a>[function <span class="apidocSignatureSpan">antd.</span>Timeline ()](#apidoc.element.antd.Timeline)
- description and source-code
```javascript
function Timeline() {
    (0, _classCallCheck3["default"])(this, Timeline);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Timeline.Item"></a>[function <span class="apidocSignatureSpan">antd.</span>Timeline.Item ()](#apidoc.element.antd.Timeline.Item)
- description and source-code
```javascript
function TimelineItem() {
    (0, _classCallCheck3["default"])(this, TimelineItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip"></a>[function <span class="apidocSignatureSpan">antd.</span>Tooltip (props)](#apidoc.element.antd.Tooltip)
- description and source-code
```javascript
function Tooltip(props) {
    (0, _classCallCheck3["default"])(this, Tooltip);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onVisibleChange = function (visible) {
        var onVisibleChange = _this.props.onVisibleChange;

        if (!('visible' in _this.props)) {
            _this.setState({ visible: _this.isNoTitle() ? false : visible });
        }
        if (onVisibleChange && !_this.isNoTitle()) {
            onVisibleChange(visible);
        }
    };
    // 动态设置动画点
    _this.onPopupAlign = function (domNode, align) {
        var placements = _this.getPlacements();
        // 当前返回的位置
        var placement = Object.keys(placements).filter(function (key) {
            return placements[key].points[0] === align.points[0] && placements[key].points[1] === align.points[1];
        })[0];
        if (!placement) {
            return;
        }
        // 根据当前坐标设置动画点
        var rect = domNode.getBoundingClientRect();
        var transformOrigin = {
            top: '50%',
            left: '50%'
        };
        if (placement.indexOf('top') >= 0 || placement.indexOf('Bottom') >= 0) {
            transformOrigin.top = rect.height - align.offset[1] + 'px';
        } else if (placement.indexOf('Top') >= 0 || placement.indexOf('bottom') >= 0) {
            transformOrigin.top = -align.offset[1] + 'px';
        }
        if (placement.indexOf('left') >= 0 || placement.indexOf('Right') >= 0) {
            transformOrigin.left = rect.width - align.offset[0] + 'px';
        } else if (placement.indexOf('right') >= 0 || placement.indexOf('Left') >= 0) {
            transformOrigin.left = -align.offset[0] + 'px';
        }
        domNode.style.transformOrigin = transformOrigin.left + ' ' + transformOrigin.top;
    };
    _this.state = {
        visible: !!props.visible
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer"></a>[function <span class="apidocSignatureSpan">antd.</span>Transfer ()](#apidoc.element.antd.Transfer)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree"></a>[function <span class="apidocSignatureSpan">antd.</span>Tree ()](#apidoc.element.antd.Tree)
- description and source-code
```javascript
function Tree() {
    (0, _classCallCheck3["default"])(this, Tree);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component2.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode"></a>[function <span class="apidocSignatureSpan">antd.</span>Tree.TreeNode (props)](#apidoc.element.antd.Tree.TreeNode)
- description and source-code
```javascript
function TreeNode(props) {
  _classCallCheck(this, TreeNode);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  ['onExpand', 'onCheck', 'onContextMenu', 'onMouseEnter', 'onMouseLeave', 'onDragStart', 'onDragEnter', 'onDragOver', 'onDragLeave
', 'onDrop', 'onDragEnd'].forEach(function (m) {
    _this[m] = _this[m].bind(_this);
  });
  _this.state = {
    dataLoading: false,
    dragNodeHighlight: false
  };
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.TreeSelect"></a>[function <span class="apidocSignatureSpan">antd.</span>TreeSelect ()](#apidoc.element.antd.TreeSelect)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload"></a>[function <span class="apidocSignatureSpan">antd.</span>Upload (props)](#apidoc.element.antd.Upload)
- description and source-code
```javascript
function Upload(props) {
    (0, _classCallCheck3["default"])(this, Upload);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onStart = function (file) {
        var targetItem = void 0;
        var nextFileList = _this.state.fileList.concat();
        if (file.length > 0) {
            targetItem = file.map(function (f) {
                var fileObject = (0, _utils.fileToObject)(f);
                fileObject.status = 'uploading';
                return fileObject;
            });
            nextFileList = nextFileList.concat(targetItem);
        } else {
            targetItem = (0, _utils.fileToObject)(file);
            targetItem.status = 'uploading';
            nextFileList.push(targetItem);
        }
        _this.onChange({
            file: targetItem,
            fileList: nextFileList
        });
        // fix ie progress
        if (!window.FormData) {
            _this.autoUpdateProgress(0, targetItem);
        }
    };
    _this.onSuccess = function (response, file) {
        _this.clearProgressTimer();
        try {
            if (typeof response === 'string') {
                response = JSON.parse(response);
            }
        } catch (e) {}
        var fileList = _this.state.fileList;
        var targetItem = (0, _utils.getFileItem)(file, fileList);
        // removed
        if (!targetItem) {
            return;
        }
        targetItem.status = 'done';
        targetItem.response = response;
        _this.onChange({
            file: (0, _extends3["default"])({}, targetItem),
            fileList: fileList
        });
    };
    _this.onProgress = function (e, file) {
        var fileList = _this.state.fileList;
        var targetItem = (0, _utils.getFileItem)(file, fileList);
        // removed
        if (!targetItem) {
            return;
        }
        targetItem.percent = e.percent;
        _this.onChange({
            event: e,
            file: (0, _extends3["default"])({}, targetItem),
            fileList: _this.state.fileList
        });
    };
    _this.onError = function (error, response, file) {
        _this.clearProgressTimer();
        var fileList = _this.state.fileList;
        var targetItem = (0, _utils.getFileItem)(file, fileList);
        // removed
        if (!targetItem) {
            return;
        }
        targetItem.error = error;
        targetItem.response = response;
        targetItem.status = 'error';
        _this.onChange({
            file: (0, _extends3["default"])({}, targetItem),
            fileList: fileList
        });
    };
    _this.handleManualRemove = function (file) {
        _this.refs.upload.abort(file);
        file.status = 'removed'; // eslint-disable-line
        _this.handleRemove(file);
    };
    _this.onChange = function (info) {
        if (!('fileList' in _this.props)) {
            _this.setState({ fileList: info.fileList });
        }
        var onChange = _this.props.onChange;

        if (onChange) {
            onChange(info);
        }
    };
    _this.onFileDrop = function (e) {
        _this.setState({
            dragState: e.type
        });
    };
    _this.state = {
        fileList: _this.props.fileList || _this.props.defaultFileList || [],
        dragState: 'drop'
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.Dragger"></a>[function <span class="apidocSignatureSpan">antd.</span>Upload.Dragger ()](#apidoc.element.antd.Upload.Dragger)
- description and source-code
```javascript
function Dragger() {
    (0, _classCallCheck3["default"])(this, Dragger);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Affix"></a>[module antd.Affix](#apidoc.module.antd.Affix)

#### <a name="apidoc.element.antd.Affix.Affix"></a>[function <span class="apidocSignatureSpan">antd.</span>Affix (props)](#apidoc.element.antd.Affix.Affix)
- description and source-code
```javascript
function Affix(props) {
    (0, _classCallCheck3["default"])(this, Affix);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.state = {
        affixStyle: null,
        placeholderStyle: null
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Affix.propTypes"></a>[module antd.Affix.propTypes](#apidoc.module.antd.Affix.propTypes)

#### <a name="apidoc.element.antd.Affix.propTypes.offsetBottom"></a>[function <span class="apidocSignatureSpan">antd.Affix.propTypes.</span>offsetBottom ()](#apidoc.element.antd.Affix.propTypes.offsetBottom)
- description and source-code
```javascript
offsetBottom = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.propTypes.offsetTop"></a>[function <span class="apidocSignatureSpan">antd.Affix.propTypes.</span>offsetTop ()](#apidoc.element.antd.Affix.propTypes.offsetTop)
- description and source-code
```javascript
offsetTop = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.propTypes.target"></a>[function <span class="apidocSignatureSpan">antd.Affix.propTypes.</span>target ()](#apidoc.element.antd.Affix.propTypes.target)
- description and source-code
```javascript
target = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Affix.prototype"></a>[module antd.Affix.prototype](#apidoc.module.antd.Affix.prototype)

#### <a name="apidoc.element.antd.Affix.prototype.clearScrollEventListeners"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>clearScrollEventListeners ()](#apidoc.element.antd.Affix.prototype.clearScrollEventListeners)
- description and source-code
```javascript
function clearScrollEventListeners() {
    var _this4 = this;

    ['scrollEvent', 'resizeEvent'].forEach(function (name) {
        if (_this4[name]) {
            _this4[name].remove();
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>componentDidMount ()](#apidoc.element.antd.Affix.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    var _this3 = this;

    var target = this.props.target || getDefaultTarget;
    // Wait for parent component ref has its value
    this.timeout = setTimeout(function () {
        _this3.setTargetEventListeners(target);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Affix.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if (this.props.target !== nextProps.target) {
        this.clearScrollEventListeners();
        this.setTargetEventListeners(nextProps.target);
        // Mock Event object.
        this.updatePosition({});
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Affix.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    this.clearScrollEventListeners();
    clearTimeout(this.timeout);
    this.updatePosition.cancel();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>render ()](#apidoc.element.antd.Affix.prototype.render)
- description and source-code
```javascript
function render() {
    var className = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, this.props.prefixCls || 'ant-affix', this.
state.affixStyle));
    var props = (0, _omit2["default"])(this.props, ['prefixCls', 'offsetTop', 'offsetBottom', 'target', 'onChange']);
    var placeholderStyle = (0, _extends3["default"])({}, this.state.placeholderStyle, this.props.style);
    return _react2["default"].createElement(
        "div",
        (0, _extends3["default"])({}, props, { style: placeholderStyle }),
        _react2["default"].createElement(
            "div",
            { className: className, ref: "fixedNode", style: this.state.affixStyle },
            this.props.children
        )
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Affix.prototype.setAffixStyle"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>setAffixStyle (e, affixStyle)](#apidoc.element.antd.Affix.prototype.setAffixStyle)
- description and source-code
```javascript
function setAffixStyle(e, affixStyle) {
    var _this2 = this;

    var _props = this.props,
        _props$onChange = _props.onChange,
        onChange = _props$onChange === undefined ? noop : _props$onChange,
        _props$target = _props.target,
        target = _props$target === undefined ? getDefaultTarget : _props$target;

    var originalAffixStyle = this.state.affixStyle;
    var isWindow = target() === window;
    if (e.type === 'scroll' && originalAffixStyle && affixStyle && isWindow) {
        return;
    }
    if ((0, _shallowequal2["default"])(affixStyle, originalAffixStyle)) {
        return;
    }
    this.setState({ affixStyle: affixStyle }, function () {
        var affixed = !!_this2.state.affixStyle;
        if (affixStyle && !originalAffixStyle || !affixStyle && originalAffixStyle) {
            onChange(affixed);
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.setPlaceholderStyle"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>setPlaceholderStyle (placeholderStyle)](#apidoc.element.antd.Affix.prototype.setPlaceholderStyle)
- description and source-code
```javascript
function setPlaceholderStyle(placeholderStyle) {
    var originalPlaceholderStyle = this.state.placeholderStyle;
    if ((0, _shallowequal2["default"])(placeholderStyle, originalPlaceholderStyle)) {
        return;
    }
    this.setState({ placeholderStyle: placeholderStyle });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.setTargetEventListeners"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>setTargetEventListeners (getTarget)](#apidoc.element.antd.Affix.prototype.setTargetEventListeners)
- description and source-code
```javascript
function setTargetEventListeners(getTarget) {
    var target = getTarget();
    if (!target) {
        return;
    }
    this.clearScrollEventListeners();
    this.scrollEvent = (0, _addEventListener2["default"])(target, 'scroll', this.updatePosition);
    this.resizeEvent = (0, _addEventListener2["default"])(target, 'resize', this.updatePosition);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Affix.prototype.updatePosition"></a>[function <span class="apidocSignatureSpan">antd.Affix.prototype.</span>updatePosition (e)](#apidoc.element.antd.Affix.prototype.updatePosition)
- description and source-code
```javascript
function updatePosition(e) {
    var _props2 = this.props,
        offsetTop = _props2.offsetTop,
        offsetBottom = _props2.offsetBottom,
        offset = _props2.offset,
        _props2$target = _props2.target,
        target = _props2$target === undefined ? getDefaultTarget : _props2$target;

    var targetNode = target();
    // Backwards support
    offsetTop = offsetTop || offset;
    var scrollTop = (0, _getScroll2["default"])(targetNode, true);
    var affixNode = _reactDom2["default"].findDOMNode(this);
    var elemOffset = getOffset(affixNode, targetNode);
    var elemSize = {
        width: this.refs.fixedNode.offsetWidth,
        height: this.refs.fixedNode.offsetHeight
    };
    var offsetMode = {
        top: false,
        bottom: false
    };
    // Default to 'offsetTop=0'.
    if (typeof offsetTop !== 'number' && typeof offsetBottom !== 'number') {
        offsetMode.top = true;
        offsetTop = 0;
    } else {
        offsetMode.top = typeof offsetTop === 'number';
        offsetMode.bottom = typeof offsetBottom === 'number';
    }
    var targetRect = getTargetRect(targetNode);
    var targetInnerHeight = targetNode.innerHeight || targetNode.clientHeight;
    if (scrollTop > elemOffset.top - offsetTop && offsetMode.top) {
        // Fixed Top
        var width = elemOffset.width;
        this.setAffixStyle(e, {
            position: 'fixed',
            top: targetRect.top + offsetTop,
            left: targetRect.left + elemOffset.left,
            width: width
        });
        this.setPlaceholderStyle({
            width: width,
            height: affixNode.offsetHeight
        });
    } else if (scrollTop < elemOffset.top + elemSize.height + offsetBottom - targetInnerHeight && offsetMode.bottom) {
        // Fixed Bottom
        var targetBottomOffet = targetNode === window ? 0 : window.innerHeight - targetRect.bottom;
        var _width = elemOffset.width;
        this.setAffixStyle(e, {
            position: 'fixed',
            bottom: targetBottomOffet + offsetBottom,
            left: targetRect.left + elemOffset.left,
            width: _width
        });
        this.setPlaceholderStyle({
            width: _width,
            height: affixNode.offsetHeight
        });
    } else {
        var affixStyle = this.state.affixStyle;

        if (e.type === 'resize' && affixStyle && affixStyle.position === 'fixed' && affixNode.offsetWidth) {
            this.setAffixStyle(e, (0, _extends3["default"])({}, affixStyle, { width: affixNode.offsetWidth }));
        } else {
            this.setAffixStyle(e, null);
        }
        this.setPlaceholderStyle(null);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Alert"></a>[module antd.Alert](#apidoc.module.antd.Alert)

#### <a name="apidoc.element.antd.Alert.Alert"></a>[function <span class="apidocSignatureSpan">antd.</span>Alert (props)](#apidoc.element.antd.Alert.Alert)
- description and source-code
```javascript
function Alert(props) {
    (0, _classCallCheck3["default"])(this, Alert);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleClose = function (e) {
        e.preventDefault();
        var dom = _reactDom2["default"].findDOMNode(_this);
        dom.style.height = dom.offsetHeight + 'px';
        // Magic code
        // 重复一次后才能正确设置 height
        dom.style.height = dom.offsetHeight + 'px';
        _this.setState({
            closing: false
        });
        (_this.props.onClose || noop)(e);
    };
    _this.animationEnd = function () {
        _this.setState({
            closed: true,
            closing: true
        });
    };
    _this.state = {
        closing: true,
        closed: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Alert.prototype"></a>[module antd.Alert.prototype](#apidoc.module.antd.Alert.prototype)

#### <a name="apidoc.element.antd.Alert.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Alert.prototype.</span>render ()](#apidoc.element.antd.Alert.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _props = this.props,
        closable = _props.closable,
        description = _props.description,
        type = _props.type,
        _props$prefixCls = _props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? 'ant-alert' : _props$prefixCls,
        message = _props.message,
        closeText = _props.closeText,
        showIcon = _props.showIcon,
        banner = _props.banner,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        style = _props.style;
    // banner模式默认有 Icon

    showIcon = showIcon || banner;
    // banner模式默认为警告
    type = banner ? 'warning' : type;
    var iconType = '';
    switch (type) {
        case 'success':
            iconType = 'check-circle';
            break;
        case 'info':
            iconType = 'info-circle';
            break;
        case 'error':
            iconType = 'cross-circle';
            break;
        case 'warning':
            iconType = 'exclamation-circle';
            break;
        default:
            iconType = 'default';
    }
    // use outline icon in alert with description
    if (!!description) {
        iconType += '-o';
    }
    var alertCls = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-' + type, true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-close', !this.state.closing), (0, _defineProperty3
["default"])(_classNames, prefixCls + '-with-description', !!description), (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-no-icon', !showIcon), (0, _defineProperty3["default"])(_classNames, prefixCls + '-banner', !!banner), _classNames), className
);
    // closeable when closeText is assigned
    if (closeText) {
        closable = true;
    }
    var closeIcon = closable ? _react2["default"].createElement(
        'a',
        { onClick: this.handleClose, className: prefixCls + '-close-icon' },
        closeText || _react2["default"].createElement(_icon2["default"], { type: 'cross' })
    ) : null;
    return this.state.closed ? null : _react2["default"].createElement(
        _rcAnimate2["default"],
        { component: '', showProp: 'data-show', transitionName: prefixCls + '-slide-up', onEnd: this.animationEnd },
        _react2["default"].createElement(
            'div',
            { 'data-show': this.state.closing, className: alertCls, style: style },
            showIcon ? _react2["default"].createElement(_icon2["default"], { className: prefixCls + '-icon', type: iconType }) :
null,
            _react2["default"].createElement(
                'span',
                { className: prefixCls + '-message' },
                message
            ),
            _react2["default"].createElement(
                'span',
                { className: prefixCls + '-description' },
                description
            ),
            closeIcon
        )
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Anchor"></a>[module antd.Anchor](#apidoc.module.antd.Anchor)

#### <a name="apidoc.element.antd.Anchor.Anchor"></a>[function <span class="apidocSignatureSpan">antd.</span>Anchor (props)](#apidoc.element.antd.Anchor.Anchor)
- description and source-code
```javascript
function Anchor(props) {
    (0, _classCallCheck3["default"])(this, Anchor);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleScroll = function () {
        _this.setState({
            activeAnchor: _this.anchorHelper.getCurrentAnchor(_this.props.offsetTop, _this.props.bounds)
        });
    };
    _this.updateInk = function () {
        var activeAnchor = _this.anchorHelper.getCurrentActiveAnchor();
        if (activeAnchor) {
            _this.refs.ink.style.top = activeAnchor.offsetTop + activeAnchor.clientHeight / 2 - 4.5 + 'px';
        }
    };
    _this.clickAnchorLink = function (href, component) {
        _this._avoidInk = true;
        _this.refs.ink.style.top = component.offsetTop + component.clientHeight / 2 - 4.5 + 'px';
        _this.anchorHelper.scrollTo(href, _this.props.offsetTop, _anchorHelper.getDefaultTarget, function () {
            _this._avoidInk = false;
        });
    };
    _this.renderAnchorLink = function (child) {
        var href = child.props.href;

        if (child.type.__ANT_ANCHOR_LINK && href) {
            _this.anchorHelper.addLink(href);
            return _react2["default"].cloneElement(child, {
                onClick: _this.clickAnchorLink,
                prefixCls: _this.props.prefixCls,
                bounds: _this.props.bounds,
                affix: _this.props.affix || _this.props.showInkInFixed,
                offsetTop: _this.props.offsetTop
            });
        }
        return child;
    };
    _this.state = {
        activeAnchor: null,
        animated: true
    };
    _this.anchorHelper = new _anchorHelper2["default"]();
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.Link"></a>[function <span class="apidocSignatureSpan">antd.Anchor.</span>Link ()](#apidoc.element.antd.Anchor.Link)
- description and source-code
```javascript
function AnchorLink() {
    (0, _classCallCheck3["default"])(this, AnchorLink);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.renderAnchorLink = function (child) {
        var href = child.props.href;

        if (href) {
            _this.context.anchorHelper.addLink(href);
            return _react2["default"].cloneElement(child, {
                onClick: _this.props.onClick,
                prefixCls: _this.props.prefixCls,
                affix: _this.props.affix,
                offsetTop: _this.props.offsetTop
            });
        }
        return child;
    };
    _this.refsTo = function (component) {
        _this._component = component;
    };
    _this.scrollTo = function (e) {
        e.preventDefault();
        var _this$props = _this.props,
            onClick = _this$props.onClick,
            href = _this$props.href;
        var anchorHelper = _this.context.anchorHelper;

        if (onClick) {
            onClick(href, _this._component);
        } else {
            var scrollToFn = anchorHelper ? anchorHelper.scrollTo : _anchorHelper.scrollTo;
            scrollToFn(href, _this.props.offsetTop);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Anchor.Link"></a>[module antd.Anchor.Link](#apidoc.module.antd.Anchor.Link)

#### <a name="apidoc.element.antd.Anchor.Link.Link"></a>[function <span class="apidocSignatureSpan">antd.Anchor.</span>Link ()](#apidoc.element.antd.Anchor.Link.Link)
- description and source-code
```javascript
function AnchorLink() {
    (0, _classCallCheck3["default"])(this, AnchorLink);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.renderAnchorLink = function (child) {
        var href = child.props.href;

        if (href) {
            _this.context.anchorHelper.addLink(href);
            return _react2["default"].cloneElement(child, {
                onClick: _this.props.onClick,
                prefixCls: _this.props.prefixCls,
                affix: _this.props.affix,
                offsetTop: _this.props.offsetTop
            });
        }
        return child;
    };
    _this.refsTo = function (component) {
        _this._component = component;
    };
    _this.scrollTo = function (e) {
        e.preventDefault();
        var _this$props = _this.props,
            onClick = _this$props.onClick,
            href = _this$props.href;
        var anchorHelper = _this.context.anchorHelper;

        if (onClick) {
            onClick(href, _this._component);
        } else {
            var scrollToFn = anchorHelper ? anchorHelper.scrollTo : _anchorHelper.scrollTo;
            scrollToFn(href, _this.props.offsetTop);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Anchor.Link.prototype"></a>[module antd.Anchor.Link.prototype](#apidoc.module.antd.Anchor.Link.prototype)

#### <a name="apidoc.element.antd.Anchor.Link.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>componentDidMount ()](#apidoc.element.antd.Anchor.Link.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    this.setActiveAnchor();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.Link.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.Anchor.Link.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
    this.setActiveAnchor();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.Link.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>render ()](#apidoc.element.antd.Anchor.Link.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _props2 = this.props,
        prefixCls = _props2.prefixCls,
        href = _props2.href,
        children = _props2.children,
        title = _props2.title,
        bounds = _props2.bounds,
        offsetTop = _props2.offsetTop,
        affix = _props2.affix;
    var anchorHelper = this.context.anchorHelper;

    var active = affix && anchorHelper && anchorHelper.getCurrentAnchor(offsetTop, bounds) === href;
    var cls = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls + '-link',
true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-link-active', active), _classNames));
    return _react2["default"].createElement(
        'div',
        { className: cls },
        _react2["default"].createElement(
            'a',
            { ref: this.refsTo, className: prefixCls + '-link-title', onClick: this.scrollTo, href: href, title: typeof title === '
string' ? title : '' },
            title
        ),
        _react2["default"].Children.map(children, this.renderAnchorLink)
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Anchor.Link.prototype.setActiveAnchor"></a>[function <span class="apidocSignatureSpan">antd.Anchor.Link.prototype.</span>setActiveAnchor ()](#apidoc.element.antd.Anchor.Link.prototype.setActiveAnchor)
- description and source-code
```javascript
function setActiveAnchor() {
    var _props = this.props,
        bounds = _props.bounds,
        offsetTop = _props.offsetTop,
        href = _props.href,
        affix = _props.affix;
    var anchorHelper = this.context.anchorHelper;

    var active = affix && anchorHelper && anchorHelper.getCurrentAnchor(offsetTop, bounds) === href;
    if (active && anchorHelper) {
        anchorHelper.setActiveAnchor(this._component);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Anchor.childContextTypes"></a>[module antd.Anchor.childContextTypes](#apidoc.module.antd.Anchor.childContextTypes)

#### <a name="apidoc.element.antd.Anchor.childContextTypes.anchorHelper"></a>[function <span class="apidocSignatureSpan">antd.Anchor.childContextTypes.</span>anchorHelper ()](#apidoc.element.antd.Anchor.childContextTypes.anchorHelper)
- description and source-code
```javascript
anchorHelper = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Anchor.prototype"></a>[module antd.Anchor.prototype](#apidoc.module.antd.Anchor.prototype)

#### <a name="apidoc.element.antd.Anchor.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>componentDidMount ()](#apidoc.element.antd.Anchor.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    this.handleScroll();
    this.updateInk();
    this.scrollEvent = (0, _addEventListener2["default"])((this.props.target || _anchorHelper.getDefaultTarget)(), 'scroll', this
.handleScroll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.Anchor.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
    if (!this._avoidInk) {
        this.updateInk();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Anchor.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    if (this.scrollEvent) {
        this.scrollEvent.remove();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>getChildContext ()](#apidoc.element.antd.Anchor.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
    return {
        anchorHelper: this.anchorHelper
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Anchor.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Anchor.prototype.</span>render ()](#apidoc.element.antd.Anchor.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _props = this.props,
        prefixCls = _props.prefixCls,
        offsetTop = _props.offsetTop,
        style = _props.style,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        affix = _props.affix,
        showInkInFixed = _props.showInkInFixed;
    var _state = this.state,
        activeAnchor = _state.activeAnchor,
        animated = _state.animated;

    var inkClass = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls + '-ink
-ball', true), (0, _defineProperty3["default"])(_classNames, 'animated', animated), (0, _defineProperty3["default"])(_classNames
, 'visible', !!activeAnchor), _classNames));
    var wrapperClass = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-wrapper', true), className
);
    var anchorClass = (0, _classnames2["default"])(prefixCls, {
        'fixed': !affix && !showInkInFixed
    });
    var anchorContent = _react2["default"].createElement(
        'div',
        { className: wrapperClass, style: style },
        _react2["default"].createElement(
            'div',
            { className: anchorClass },
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-ink' },
                _react2["default"].createElement('span', { className: inkClass, ref: 'ink' })
            ),
            _react2["default"].Children.toArray(this.props.children).map(this.renderAnchorLink)
        )
    );
    return !affix ? anchorContent : _react2["default"].createElement(
        _affix2["default"],
        { offsetTop: offsetTop },
        anchorContent
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.AutoComplete"></a>[module antd.AutoComplete](#apidoc.module.antd.AutoComplete)

#### <a name="apidoc.element.antd.AutoComplete.AutoComplete"></a>[function <span class="apidocSignatureSpan">antd.</span>AutoComplete ()](#apidoc.element.antd.AutoComplete.AutoComplete)
- description and source-code
```javascript
function AutoComplete() {
    (0, _classCallCheck3["default"])(this, AutoComplete);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.getInputElement = function () {
        var children = _this.props.children;

        var element = children && _react2["default"].isValidElement(children) && children.type !== _rcSelect.Option ? _react2["default
"].Children.only(_this.props.children) : _react2["default"].createElement(_input2["default"], null);
        return _react2["default"].createElement(
            _InputElement2["default"],
            { className: 'ant-input' },
            element
        );
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.AutoComplete.OptGroup"></a>[function <span class="apidocSignatureSpan">antd.AutoComplete.</span>OptGroup ()](#apidoc.element.antd.AutoComplete.OptGroup)
- description and source-code
```javascript
function OptGroup() {
  (0, _classCallCheck3["default"])(this, OptGroup);
  return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.AutoComplete.Option"></a>[function <span class="apidocSignatureSpan">antd.AutoComplete.</span>Option ()](#apidoc.element.antd.AutoComplete.Option)
- description and source-code
```javascript
function Option() {
  (0, _classCallCheck3["default"])(this, Option);
  return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.AutoComplete.prototype"></a>[module antd.AutoComplete.prototype](#apidoc.module.antd.AutoComplete.prototype)

#### <a name="apidoc.element.antd.AutoComplete.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.AutoComplete.prototype.</span>render ()](#apidoc.element.antd.AutoComplete.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _props = this.props,
        size = _props.size,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        notFoundContent = _props.notFoundContent,
        prefixCls = _props.prefixCls,
        optionLabelProp = _props.optionLabelProp,
        dataSource = _props.dataSource,
        children = _props.children;

    var cls = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls + '-lg', size
 === 'large'), (0, _defineProperty3["default"])(_classNames, prefixCls + '-sm', size === 'small'), (0, _defineProperty3["default
"])(_classNames, className, !!className), (0, _defineProperty3["default"])(_classNames, prefixCls + '-show-search', true), (0, _defineProperty3
["default"])(_classNames, prefixCls + '-auto-complete', true), _classNames));
    var options = void 0;
    var childArray = _react2["default"].Children.toArray(children);
    if (childArray.length && isSelectOptionOrSelectOptGroup(childArray[0])) {
        options = children;
    } else {
        options = dataSource ? dataSource.map(function (item) {
            if (_react2["default"].isValidElement(item)) {
                return item;
            }
            switch (typeof item === 'undefined' ? 'undefined' : (0, _typeof3["default"])(item)) {
                case 'string':
                    return _react2["default"].createElement(
                        _rcSelect.Option,
                        { key: item },
                        item
                    );
                case 'object':
                    return _react2["default"].createElement(
                        _rcSelect.Option,
                        { key: item.value },
                        item.text
                    );
                default:
                    throw new Error('AutoComplete[dataSource] only supports type 'string[] | Object[]'.');
            }
        }) : [];
    }
    return _react2["default"].createElement(
        _select2["default"],
        (0, _extends3["default"])({}, this.props, { className: cls, mode: 'combobox', optionLabelProp: optionLabelProp, getInputElement
: this.getInputElement, notFoundContent: notFoundContent }),
        options
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.BackTop"></a>[module antd.BackTop](#apidoc.module.antd.BackTop)

#### <a name="apidoc.element.antd.BackTop.BackTop"></a>[function <span class="apidocSignatureSpan">antd.</span>BackTop (props)](#apidoc.element.antd.BackTop.BackTop)
- description and source-code
```javascript
function BackTop(props) {
    (0, _classCallCheck3["default"])(this, BackTop);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.getCurrentScrollTop = function () {
        var targetNode = (_this.props.target || getDefaultTarget)();
        if (targetNode === window) {
            return window.pageYOffset || document.body.scrollTop || document.documentElement.scrollTop;
        }
        return targetNode.scrollTop;
    };
    _this.scrollToTop = function (e) {
        var scrollTop = _this.getCurrentScrollTop();
        var startTime = Date.now();
        var frameFunc = function frameFunc() {
            var timestamp = Date.now();
            var time = timestamp - startTime;
            _this.setScrollTop(easeInOutCubic(time, scrollTop, 0, 450));
            if (time < 450) {
                reqAnimFrame(frameFunc);
            }
        };
        reqAnimFrame(frameFunc);
        (_this.props.onClick || noop)(e);
    };
    _this.handleScroll = function () {
        var _this$props = _this.props,
            visibilityHeight = _this$props.visibilityHeight,
            _this$props$target = _this$props.target,
            target = _this$props$target === undefined ? getDefaultTarget : _this$props$target;

        var scrollTop = (0, _getScroll2["default"])(target(), true);
        _this.setState({
            visible: scrollTop > visibilityHeight
        });
    };
    _this.state = {
        visible: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.BackTop.prototype"></a>[module antd.BackTop.prototype](#apidoc.module.antd.BackTop.prototype)

#### <a name="apidoc.element.antd.BackTop.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>componentDidMount ()](#apidoc.element.antd.BackTop.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    this.handleScroll();
    this.scrollEvent = (0, _addEventListener2["default"])((this.props.target || getDefaultTarget)(), 'scroll', this.handleScroll
);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.BackTop.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.BackTop.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    if (this.scrollEvent) {
        this.scrollEvent.remove();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.BackTop.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>render ()](#apidoc.element.antd.BackTop.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        _props$prefixCls = _props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? 'ant-back-top' : _props$prefixCls,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        children = _props.children;

    var classString = (0, _classnames2["default"])(prefixCls, className);
    var defaultElement = _react2["default"].createElement(
        'div',
        { className: prefixCls + '-content' },
        _react2["default"].createElement(_icon2["default"], { className: prefixCls + '-icon', type: 'to-top' })
    );
    // fix https://fb.me/react-unknown-prop
    var divProps = (0, _omit2["default"])(this.props, ['prefixCls', 'className', 'children', 'visibilityHeight']);
    var backTopBtn = this.state.visible ? _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({}, divProps, { className: classString, onClick: this.scrollToTop }),
        children || defaultElement
    ) : null;
    return _react2["default"].createElement(
        _rcAnimate2["default"],
        { component: '', transitionName: 'fade' },
        backTopBtn
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.BackTop.prototype.setScrollTop"></a>[function <span class="apidocSignatureSpan">antd.BackTop.prototype.</span>setScrollTop (value)](#apidoc.element.antd.BackTop.prototype.setScrollTop)
- description and source-code
```javascript
function setScrollTop(value) {
    var targetNode = (this.props.target || getDefaultTarget)();
    if (targetNode === window) {
        document.body.scrollTop = value;
        document.documentElement.scrollTop = value;
    } else {
        targetNode.scrollTop = value;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Badge"></a>[module antd.Badge](#apidoc.module.antd.Badge)

#### <a name="apidoc.element.antd.Badge.Badge"></a>[function <span class="apidocSignatureSpan">antd.</span>Badge ()](#apidoc.element.antd.Badge.Badge)
- description and source-code
```javascript
function Badge() {
    (0, _classCallCheck3["default"])(this, Badge);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Badge.propTypes"></a>[module antd.Badge.propTypes](#apidoc.module.antd.Badge.propTypes)

#### <a name="apidoc.element.antd.Badge.propTypes.count"></a>[function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>count ()](#apidoc.element.antd.Badge.propTypes.count)
- description and source-code
```javascript
count = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Badge.propTypes.dot"></a>[function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>dot ()](#apidoc.element.antd.Badge.propTypes.dot)
- description and source-code
```javascript
dot = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Badge.propTypes.overflowCount"></a>[function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>overflowCount ()](#apidoc.element.antd.Badge.propTypes.overflowCount)
- description and source-code
```javascript
overflowCount = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Badge.propTypes.showZero"></a>[function <span class="apidocSignatureSpan">antd.Badge.propTypes.</span>showZero ()](#apidoc.element.antd.Badge.propTypes.showZero)
- description and source-code
```javascript
showZero = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Badge.prototype"></a>[module antd.Badge.prototype](#apidoc.module.antd.Badge.prototype)

#### <a name="apidoc.element.antd.Badge.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Badge.prototype.</span>render ()](#apidoc.element.antd.Badge.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames, _classNames2;

    var _a = this.props,
        count = _a.count,
        showZero = _a.showZero,
        prefixCls = _a.prefixCls,
        overflowCount = _a.overflowCount,
        className = _a.className,
        style = _a.style,
        children = _a.children,
        dot = _a.dot,
        status = _a.status,
        text = _a.text,
        restProps = __rest(_a, ["count", "showZero", "prefixCls", "overflowCount", "className", "style", "children", "dot", "status
", "text"]);
    var isDot = dot || status;
    var displayCount = count > overflowCount ? overflowCount + '+' : count;
    // dot mode don't need count
    if (isDot) {
        displayCount = '';
    }
    var isZero = displayCount === '0' || displayCount === 0;
    var isEmpty = displayCount === null || displayCount === undefined || displayCount === '';
    var hidden = (isEmpty || isZero && !showZero) && !isDot;
    var scrollNumberCls = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-dot', isDot), (0, _defineProperty3["default"])(_classNames, prefixCls + '-count', !isDot), _classNames));
    var badgeCls = (0, _classnames2["default"])(className, prefixCls, (_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2
, prefixCls + '-status', !!status), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-not-a-wrapper', !children), _classNames2
));
    (0, _warning2["default"])(!(children && status), ''Badge[children]' and 'Badge[status]' cannot be used at the same time.');
    // <Badge status="success" />
    if (!children && status) {
        var _classNames3;

        var statusCls = (0, _classnames2["default"])((_classNames3 = {}, (0, _defineProperty3["default"])(_classNames3, prefixCls
 + '-status-dot', !!status), (0, _defineProperty3["default"])(_classNames3, prefixCls + '-status-' + status, true), _classNames3
));
        return _react2["default"].createElement(
            'span',
            { className: badgeCls },
            _react2["default"].createElement('span', { className: statusCls }),
            _react2["default"].createElement(
                'span',
                { className: prefixCls + '-status-text' },
                text
            )
        );
    }
    var scrollNumber = hidden ? null : _react2["default"].createElement(_ScrollNumber2["default"], { 'data-show': !hidden, className
: scrollNumberCls, count: displayCount, style: style });
    var statusText = hidden || !text ? null : _react2["default"].createElement(
        'span',
        { className: prefixCls + '-status-text' },
        text
    );
    return _react2["default"].createElement(
        'span',
        (0, _extends3["default"])({}, restProps, { className: badgeCls, title: count }),
        children,
        _react2["default"].createElement(
            _rcAnimate2["default"],
            { component: '', showProp: 'data-show', transitionName: children ? prefixCls + '-zoom' : '', transitionAppear: true },
            scrollNumber
        ),
        statusText
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Breadcrumb"></a>[module antd.Breadcrumb](#apidoc.module.antd.Breadcrumb)

#### <a name="apidoc.element.antd.Breadcrumb.Breadcrumb"></a>[function <span class="apidocSignatureSpan">antd.</span>Breadcrumb ()](#apidoc.element.antd.Breadcrumb.Breadcrumb)
- description and source-code
```javascript
function Breadcrumb() {
    (0, _classCallCheck3["default"])(this, Breadcrumb);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.Item"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.</span>Item ()](#apidoc.element.antd.Breadcrumb.Item)
- description and source-code
```javascript
function BreadcrumbItem() {
    (0, _classCallCheck3["default"])(this, BreadcrumbItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Breadcrumb.Item"></a>[module antd.Breadcrumb.Item](#apidoc.module.antd.Breadcrumb.Item)

#### <a name="apidoc.element.antd.Breadcrumb.Item.Item"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.</span>Item ()](#apidoc.element.antd.Breadcrumb.Item.Item)
- description and source-code
```javascript
function BreadcrumbItem() {
    (0, _classCallCheck3["default"])(this, BreadcrumbItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Breadcrumb.Item.prototype"></a>[module antd.Breadcrumb.Item.prototype](#apidoc.module.antd.Breadcrumb.Item.prototype)

#### <a name="apidoc.element.antd.Breadcrumb.Item.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.Item.prototype.</span>render ()](#apidoc.element.antd.Breadcrumb.Item.prototype.render)
- description and source-code
```javascript
function render() {
    var _a = this.props,
        prefixCls = _a.prefixCls,
        separator = _a.separator,
        children = _a.children,
        restProps = __rest(_a, ["prefixCls", "separator", "children"]);
    var link = void 0;
    if ('href' in this.props) {
        link = _react2["default"].createElement(
            'a',
            (0, _extends3["default"])({ className: prefixCls + '-link' }, restProps),
            children
        );
    } else {
        link = _react2["default"].createElement(
            'span',
            (0, _extends3["default"])({ className: prefixCls + '-link' }, restProps),
            children
        );
    }
    if (children) {
        return _react2["default"].createElement(
            'span',
            null,
            link,
            _react2["default"].createElement(
                'span',
                { className: prefixCls + '-separator' },
                separator
            )
        );
    }
    return null;
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Breadcrumb.propTypes"></a>[module antd.Breadcrumb.propTypes](#apidoc.module.antd.Breadcrumb.propTypes)

#### <a name="apidoc.element.antd.Breadcrumb.propTypes.linkRender"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>linkRender ()](#apidoc.element.antd.Breadcrumb.propTypes.linkRender)
- description and source-code
```javascript
linkRender = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.propTypes.nameRender"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>nameRender ()](#apidoc.element.antd.Breadcrumb.propTypes.nameRender)
- description and source-code
```javascript
nameRender = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.propTypes.params"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>params ()](#apidoc.element.antd.Breadcrumb.propTypes.params)
- description and source-code
```javascript
params = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>prefixCls ()](#apidoc.element.antd.Breadcrumb.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.propTypes.routes"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>routes ()](#apidoc.element.antd.Breadcrumb.propTypes.routes)
- description and source-code
```javascript
routes = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.propTypes.separator"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.propTypes.</span>separator ()](#apidoc.element.antd.Breadcrumb.propTypes.separator)
- description and source-code
```javascript
separator = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Breadcrumb.prototype"></a>[module antd.Breadcrumb.prototype](#apidoc.module.antd.Breadcrumb.prototype)

#### <a name="apidoc.element.antd.Breadcrumb.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.prototype.</span>componentDidMount ()](#apidoc.element.antd.Breadcrumb.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    var props = this.props;
    (0, _warning2["default"])(!('linkRender' in props || 'nameRender' in props), ''linkRender' and 'nameRender' are removed, please
 use 'itemRender' instead, ' + 'see: http://u.ant.design/item-render.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Breadcrumb.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Breadcrumb.prototype.</span>render ()](#apidoc.element.antd.Breadcrumb.prototype.render)
- description and source-code
```javascript
function render() {
    var crumbs = void 0;
    var _props = this.props,
        separator = _props.separator,
        prefixCls = _props.prefixCls,
        style = _props.style,
        className = _props.className,
        routes = _props.routes,
        _props$params = _props.params,
        params = _props$params === undefined ? {} : _props$params,
        children = _props.children,
        _props$itemRender = _props.itemRender,
        itemRender = _props$itemRender === undefined ? defaultItemRender : _props$itemRender;

    if (routes && routes.length > 0) {
        var paths = [];
        crumbs = routes.map(function (route) {
            route.path = route.path || '';
            var path = route.path.replace(/^\//, '');
            Object.keys(params).forEach(function (key) {
                path = path.replace(':' + key, params[key]);
            });
            if (path) {
                paths.push(path);
            }
            return _react2["default"].createElement(
                _BreadcrumbItem2["default"],
                { separator: separator, key: route.breadcrumbName || path },
                itemRender(route, params, routes, paths)
            );
        });
    } else if (children) {
        crumbs = _react2["default"].Children.map(children, function (element, index) {
            if (!element) {
                return element;
            }
            (0, _warning2["default"])(element.type && element.type.__ANT_BREADCRUMB_ITEM, 'Breadcrumb only accepts Breadcrumb.Item
 as it\'s children');
            return (0, _react.cloneElement)(element, {
                separator: separator,
                key: index
            });
        });
    }
    return _react2["default"].createElement(
        'div',
        { className: (0, _classnames2["default"])(className, prefixCls), style: style },
        crumbs
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Button"></a>[module antd.Button](#apidoc.module.antd.Button)

#### <a name="apidoc.element.antd.Button.Button"></a>[function <span class="apidocSignatureSpan">antd.</span>Button (props)](#apidoc.element.antd.Button.Button)
- description and source-code
```javascript
function Button(props) {
    (0, _classCallCheck3["default"])(this, Button);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleClick = function (e) {
        // Add click effect
        _this.setState({ clicked: true });
        clearTimeout(_this.timeout);
        _this.timeout = setTimeout(function () {
            return _this.setState({ clicked: false });
        }, 500);
        var onClick = _this.props.onClick;
        if (onClick) {
            onClick(e);
        }
    };
    // Handle auto focus when click button in Chrome
    _this.handleMouseUp = function (e) {
        (0, _reactDom.findDOMNode)(_this).blur();
        if (_this.props.onMouseUp) {
            _this.props.onMouseUp(e);
        }
    };
    _this.state = {
        loading: props.loading
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.Group"></a>[function <span class="apidocSignatureSpan">antd.Button.</span>Group (props)](#apidoc.element.antd.Button.Group)
- description and source-code
```javascript
function ButtonGroup(props) {
    var _props$prefixCls = props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? 'ant-btn-group' : _props$prefixCls,
        _props$size = props.size,
        size = _props$size === undefined ? '' : _props$size,
        className = props.className,
        others = __rest(props, ["prefixCls", "size", "className"]);
    // large => lg
    // small => sm


    var sizeCls = {
        large: 'lg',
        small: 'sm'
    }[size] || '';
    var classes = (0, _classnames2["default"])(prefixCls, (0, _defineProperty3["default"])({}, prefixCls + '-' + sizeCls, sizeCls
), className);
    return _react2["default"].createElement('div', (0, _extends3["default"])({}, others, { className: classes }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Button.propTypes"></a>[module antd.Button.propTypes](#apidoc.module.antd.Button.propTypes)

#### <a name="apidoc.element.antd.Button.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>className ()](#apidoc.element.antd.Button.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.htmlType"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>htmlType ()](#apidoc.element.antd.Button.propTypes.htmlType)
- description and source-code
```javascript
htmlType = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.icon"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>icon ()](#apidoc.element.antd.Button.propTypes.icon)
- description and source-code
```javascript
icon = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.loading"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>loading ()](#apidoc.element.antd.Button.propTypes.loading)
- description and source-code
```javascript
loading = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.onClick"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>onClick ()](#apidoc.element.antd.Button.propTypes.onClick)
- description and source-code
```javascript
onClick = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.shape"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>shape ()](#apidoc.element.antd.Button.propTypes.shape)
- description and source-code
```javascript
shape = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.size"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>size ()](#apidoc.element.antd.Button.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.propTypes.type"></a>[function <span class="apidocSignatureSpan">antd.Button.propTypes.</span>type ()](#apidoc.element.antd.Button.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Button.prototype"></a>[module antd.Button.prototype](#apidoc.module.antd.Button.prototype)

#### <a name="apidoc.element.antd.Button.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Button.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Button.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    var _this2 = this;

    var currentLoading = this.props.loading;
    var loading = nextProps.loading;
    if (currentLoading) {
        clearTimeout(this.delayTimeout);
    }
    if (loading && loading.delay) {
        this.delayTimeout = setTimeout(function () {
            return _this2.setState({ loading: loading });
        }, loading.delay);
    } else {
        this.setState({ loading: loading });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Button.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Button.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    if (this.timeout) {
        clearTimeout(this.timeout);
    }
    if (this.delayTimeout) {
        clearTimeout(this.delayTimeout);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Button.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Button.prototype.</span>render ()](#apidoc.element.antd.Button.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        type = _a.type,
        shape = _a.shape,
        _a$size = _a.size,
        size = _a$size === undefined ? '' : _a$size,
        className = _a.className,
        htmlType = _a.htmlType,
        children = _a.children,
        icon = _a.icon,
        prefixCls = _a.prefixCls,
        ghost = _a.ghost,
        others = __rest(_a, ["type", "shape", "size", "className", "htmlType", "children", "icon", "prefixCls", "ghost"]);var _state
 = this.state,
        loading = _state.loading,
        clicked = _state.clicked;
    // large => lg
    // small => sm

    var sizeCls = {
        large: 'lg',
        small: 'sm'
    }[size] || '';
    var classes = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-' + type, type), (0, _defineProperty3["default"])(_classNames, prefixCls + '-' + shape, shape), (0, _defineProperty3["default
"])(_classNames, prefixCls + '-' + sizeCls, sizeCls), (0, _defineProperty3["default"])(_classNames, prefixCls + '-icon-only', !children
 && icon), (0, _defineProperty3["default"])(_classNames, prefixCls + '-loading', loading), (0, _defineProperty3["default"])(_classNames
, prefixCls + '-clicked', clicked), (0, _defineProperty3["default"])(_classNames, prefixCls + '-background-ghost', ghost), _classNames
), className);
    var iconType = loading ? 'loading' : icon;
    var iconNode = iconType ? _react2["default"].createElement(_icon2["default"], { type: iconType }) : null;
    var kids = _react2["default"].Children.map(children, insertSpace);
    return _react2["default"].createElement(
        'button',
        (0, _extends3["default"])({}, (0, _omit2["default"])(others, ['loading', 'clicked']), { type: htmlType || 'button', className
: classes, onMouseUp: this.handleMouseUp, onClick: this.handleClick }),
        iconNode,
        kids
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Calendar"></a>[module antd.Calendar](#apidoc.module.antd.Calendar)

#### <a name="apidoc.element.antd.Calendar.Calendar"></a>[function <span class="apidocSignatureSpan">antd.</span>Calendar (props, context)](#apidoc.element.antd.Calendar.Calendar)
- description and source-code
```javascript
function Calendar(props, context) {
    (0, _classCallCheck3["default"])(this, Calendar);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props, context));

    _this.monthCellRender = function (value) {
        var _this$props = _this.props,
            prefixCls = _this$props.prefixCls,
            _this$props$monthCell = _this$props.monthCellRender,
            monthCellRender = _this$props$monthCell === undefined ? noop : _this$props$monthCell;

        return _react2["default"].createElement(
            'div',
            { className: prefixCls + '-month' },
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-value' },
                value.localeData().monthsShort(value)
            ),
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-content' },
                monthCellRender(value)
            )
        );
    };
    _this.dateCellRender = function (value) {
        var _this$props2 = _this.props,
            prefixCls = _this$props2.prefixCls,
            _this$props2$dateCell = _this$props2.dateCellRender,
            dateCellRender = _this$props2$dateCell === undefined ? noop : _this$props2$dateCell;

        return _react2["default"].createElement(
            'div',
            { className: prefixCls + '-date' },
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-value' },
                zerofixed(value.date())
            ),
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-content' },
                dateCellRender(value)
            )
        );
    };
    _this.setValue = function (value, way) {
        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        if (way === 'select') {
            if (_this.props.onSelect) {
                _this.props.onSelect(value);
            }
        } else if (way === 'changePanel') {
            _this.onPanelChange(value, _this.state.mode);
        }
    };
    _this.setType = function (type) {
        var mode = type === 'date' ? 'month' : 'year';
        if (_this.state.mode !== mode) {
            _this.setState({ mode: mode });
            _this.onPanelChange(_this.state.value, mode);
        }
    };
    _this.onHeaderValueChange = function (value) {
        _this.setValue(value, 'changePanel');
    };
    _this.onHeaderTypeChange = function (type) {
        _this.setType(type);
    };
    _this.onSelect = function (value) {
        _this.setValue(value, 'select');
    };
    // Make sure that moment locale had be set correctly.
    (0, _getLocale.getComponentLocale)(props, context, 'Calendar', function () {
        return require('./locale/zh_CN');
    });
    var value = props.value || props.defaultValue || (0, _moment2["default"])();
    if (!_moment2["default"].isMoment(value)) {
        throw new Error('The value/defaultValue of Calendar must be a moment object after 'antd@2.0', ' + 'see: http://u.ant.design
/calendar-value');
    }
    _this.state = {
        value: value,
        mode: props.mode
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Calendar.contextTypes"></a>[module antd.Calendar.contextTypes](#apidoc.module.antd.Calendar.contextTypes)

#### <a name="apidoc.element.antd.Calendar.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Calendar.contextTypes.</span>antLocale ()](#apidoc.element.antd.Calendar.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Calendar.defaultProps"></a>[module antd.Calendar.defaultProps](#apidoc.module.antd.Calendar.defaultProps)

#### <a name="apidoc.element.antd.Calendar.defaultProps.onPanelChange"></a>[function <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>onPanelChange ()](#apidoc.element.antd.Calendar.defaultProps.onPanelChange)
- description and source-code
```javascript
function noop() {
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.defaultProps.onSelect"></a>[function <span class="apidocSignatureSpan">antd.Calendar.defaultProps.</span>onSelect ()](#apidoc.element.antd.Calendar.defaultProps.onSelect)
- description and source-code
```javascript
function noop() {
    return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Calendar.propTypes"></a>[module antd.Calendar.propTypes](#apidoc.module.antd.Calendar.propTypes)

#### <a name="apidoc.element.antd.Calendar.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>className ()](#apidoc.element.antd.Calendar.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.dateCellRender"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>dateCellRender ()](#apidoc.element.antd.Calendar.propTypes.dateCellRender)
- description and source-code
```javascript
dateCellRender = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.dateFullCellRender"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>dateFullCellRender ()](#apidoc.element.antd.Calendar.propTypes.dateFullCellRender)
- description and source-code
```javascript
dateFullCellRender = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.fullscreen"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>fullscreen ()](#apidoc.element.antd.Calendar.propTypes.fullscreen)
- description and source-code
```javascript
fullscreen = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.locale"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>locale ()](#apidoc.element.antd.Calendar.propTypes.locale)
- description and source-code
```javascript
locale = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.monthCellRender"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>monthCellRender ()](#apidoc.element.antd.Calendar.propTypes.monthCellRender)
- description and source-code
```javascript
monthCellRender = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.monthFullCellRender"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>monthFullCellRender ()](#apidoc.element.antd.Calendar.propTypes.monthFullCellRender)
- description and source-code
```javascript
monthFullCellRender = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.onPanelChange"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>onPanelChange ()](#apidoc.element.antd.Calendar.propTypes.onPanelChange)
- description and source-code
```javascript
onPanelChange = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.onSelect"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>onSelect ()](#apidoc.element.antd.Calendar.propTypes.onSelect)
- description and source-code
```javascript
onSelect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>prefixCls ()](#apidoc.element.antd.Calendar.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.style"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>style ()](#apidoc.element.antd.Calendar.propTypes.style)
- description and source-code
```javascript
style = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.propTypes.value"></a>[function <span class="apidocSignatureSpan">antd.Calendar.propTypes.</span>value ()](#apidoc.element.antd.Calendar.propTypes.value)
- description and source-code
```javascript
value = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Calendar.prototype"></a>[module antd.Calendar.prototype](#apidoc.module.antd.Calendar.prototype)

#### <a name="apidoc.element.antd.Calendar.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Calendar.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Calendar.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('value' in nextProps) {
        this.setState({
            value: nextProps.value
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.prototype.onPanelChange"></a>[function <span class="apidocSignatureSpan">antd.Calendar.prototype.</span>onPanelChange (value, mode)](#apidoc.element.antd.Calendar.prototype.onPanelChange)
- description and source-code
```javascript
function onPanelChange(value, mode) {
    var onPanelChange = this.props.onPanelChange;

    if (onPanelChange) {
        onPanelChange(value, mode);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Calendar.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Calendar.prototype.</span>render ()](#apidoc.element.antd.Calendar.prototype.render)
- description and source-code
```javascript
function render() {
    var state = this.state,
        props = this.props,
        context = this.context;
    var value = state.value,
        mode = state.mode;

    var localeCode = (0, _getLocale.getLocaleCode)(context);
    if (value && localeCode) {
        value.locale(localeCode);
    }
    var prefixCls = props.prefixCls,
        style = props.style,
        className = props.className,
        fullscreen = props.fullscreen,
        dateFullCellRender = props.dateFullCellRender,
        monthFullCellRender = props.monthFullCellRender;

    var type = mode === 'year' ? 'month' : 'date';
    var locale = (0, _getLocale.getComponentLocale)(props, context, 'Calendar', function () {
        return require('./locale/zh_CN');
    });
    var cls = className || '';
    if (fullscreen) {
        cls += ' ' + prefixCls + '-fullscreen';
    }
    var monthCellRender = monthFullCellRender || this.monthCellRender;
    var dateCellRender = dateFullCellRender || this.dateCellRender;
    return _react2["default"].createElement(
        'div',
        { className: cls, style: style },
        _react2["default"].createElement(_Header2["default"], { fullscreen: fullscreen, type: type, value: value, locale: locale
.lang, prefixCls: prefixCls, onTypeChange: this.onHeaderTypeChange, onValueChange: this.onHeaderValueChange }),
        _react2["default"].createElement(_FullCalendar2["default"], (0, _extends3["default"])({}, props, { Select: noop, locale:
locale.lang, type: type, prefixCls: prefixCls, showHeader: false, value: value, monthCellRender: monthCellRender, dateCellRender
: dateCellRender, onSelect: this.onSelect }))
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Carousel"></a>[module antd.Carousel](#apidoc.module.antd.Carousel)

#### <a name="apidoc.element.antd.Carousel.Carousel"></a>[function <span class="apidocSignatureSpan">antd.</span>Carousel ()](#apidoc.element.antd.Carousel.Carousel)
- description and source-code
```javascript
function Carousel() {
    (0, _classCallCheck3["default"])(this, Carousel);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this));

    _this.onWindowResized = function () {
        // Fix https://github.com/ant-design/ant-design/issues/2550
        var slick = _this.refs.slick;
        var autoplay = _this.props.autoplay;

        if (autoplay && slick && slick.innerSlider && slick.innerSlider.autoPlay) {
            slick.innerSlider.autoPlay();
        }
    };
    _this.onWindowResized = (0, _lodash2["default"])(_this.onWindowResized, 500, {
        leading: false
    });
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Carousel.prototype"></a>[module antd.Carousel.prototype](#apidoc.module.antd.Carousel.prototype)

#### <a name="apidoc.element.antd.Carousel.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Carousel.prototype.</span>componentDidMount ()](#apidoc.element.antd.Carousel.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    var autoplay = this.props.autoplay;

    if (autoplay) {
        window.addEventListener('resize', this.onWindowResized);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Carousel.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Carousel.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Carousel.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    var autoplay = this.props.autoplay;

    if (autoplay) {
        window.removeEventListener('resize', this.onWindowResized);
        this.onWindowResized.cancel();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Carousel.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Carousel.prototype.</span>render ()](#apidoc.element.antd.Carousel.prototype.render)
- description and source-code
```javascript
function render() {
    var props = (0, _objectAssign2["default"])({}, this.props);
    if (props.effect === 'fade') {
        props.fade = true;
    }
    var className = props.prefixCls;
    if (props.vertical) {
        className = className + ' ' + className + '-vertical';
    }
    return _react2["default"].createElement(
        'div',
        { className: className },
        _react2["default"].createElement(_reactSlick2["default"], (0, _extends3["default"])({ ref: 'slick' }, props))
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Cascader"></a>[module antd.Cascader](#apidoc.module.antd.Cascader)

#### <a name="apidoc.element.antd.Cascader.Cascader"></a>[function <span class="apidocSignatureSpan">antd.</span>Cascader (props)](#apidoc.element.antd.Cascader.Cascader)
- description and source-code
```javascript
function Cascader(props) {
    (0, _classCallCheck3["default"])(this, Cascader);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleChange = function (value, selectedOptions) {
        _this.setState({ inputValue: '' });
        if (selectedOptions[0].__IS_FILTERED_OPTION) {
            var unwrappedValue = value[0];
            var unwrappedSelectedOptions = selectedOptions[0].path;
            _this.setValue(unwrappedValue, unwrappedSelectedOptions);
            return;
        }
        _this.setValue(value, selectedOptions);
    };
    _this.handlePopupVisibleChange = function (popupVisible) {
        _this.setState({
            popupVisible: popupVisible,
            inputFocused: popupVisible,
            inputValue: popupVisible ? _this.state.inputValue : ''
        });
        var onPopupVisibleChange = _this.props.onPopupVisibleChange;
        if (onPopupVisibleChange) {
            onPopupVisibleChange(popupVisible);
        }
    };
    _this.handleInputBlur = function () {
        _this.setState({
            inputFocused: false
        });
    };
    _this.handleInputClick = function (e) {
        var _this$state = _this.state,
            inputFocused = _this$state.inputFocused,
            popupVisible = _this$state.popupVisible;
        // Prevent 'Trigger' behaviour.

        if (inputFocused || popupVisible) {
            e.stopPropagation();
            e.nativeEvent.stopImmediatePropagation();
        }
    };
    _this.handleKeyDown = function (e) {
        if (e.keyCode === _KeyCode2["default"].BACKSPACE) {
            e.stopPropagation();
        }
    };
    _this.handleInputChange = function (e) {
        var inputValue = e.target.value;
        _this.setState({ inputValue: inputValue });
    };
    _this.setValue = function (value) {
        var selectedOptions = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : [];

        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(value, selectedOptions);
        }
    };
    _this.clearSelection = function (e) {
        e.preventDefault();
        e.stopPropagation();
        if (!_this.state.inputValue) {
            _this.setValue([]);
            _this.setState({ popupVisible: false });
        } else {
            _this.setState({ inputValue: '' });
        }
    };
    _this.state = {
        value: props.value || props.defaultValue || [],
        inputValue: '',
        inputFocused: false,
        popupVisible: false,
        flattenOptions: props.showSearch && _this.flattenTree(props.options, props.changeOnSelect)
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Cascader.prototype"></a>[module antd.Cascader.prototype](#apidoc.module.antd.Cascader.prototype)

#### <a name="apidoc.element.antd.Cascader.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Cascader.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('value' in nextProps) {
        this.setState({ value: nextProps.value || [] });
    }
    if (nextProps.showSearch && this.props.options !== nextProps.options) {
        this.setState({ flattenOptions: this.flattenTree(nextProps.options, nextProps.changeOnSelect) });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Cascader.prototype.flattenTree"></a>[function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>flattenTree (options, changeOnSelect)](#apidoc.element.antd.Cascader.prototype.flattenTree)
- description and source-code
```javascript
function flattenTree(options, changeOnSelect) {
    var _this2 = this;

    var ancestor = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : [];

    var flattenOptions = [];
    options.forEach(function (option) {
        var path = ancestor.concat(option);
        if (changeOnSelect || !option.children) {
            flattenOptions.push(path);
        }
        if (option.children) {
            flattenOptions = flattenOptions.concat(_this2.flattenTree(option.children, changeOnSelect, path));
        }
    });
    return flattenOptions;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Cascader.prototype.generateFilteredOptions"></a>[function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>generateFilteredOptions (prefixCls)](#apidoc.element.antd.Cascader.prototype.generateFilteredOptions)
- description and source-code
```javascript
function generateFilteredOptions(prefixCls) {
    var _this3 = this;

    var _props2 = this.props,
        showSearch = _props2.showSearch,
        notFoundContent = _props2.notFoundContent;
    var _showSearch$filter = showSearch.filter,
        filter = _showSearch$filter === undefined ? defaultFilterOption : _showSearch$filter,
        _showSearch$render = showSearch.render,
        render = _showSearch$render === undefined ? defaultRenderFilteredOption : _showSearch$render,
        _showSearch$sort = showSearch.sort,
        sort = _showSearch$sort === undefined ? defaultSortFilteredOption : _showSearch$sort;
    var _state = this.state,
        flattenOptions = _state.flattenOptions,
        inputValue = _state.inputValue;

    var filtered = flattenOptions.filter(function (path) {
        return filter(_this3.state.inputValue, path);
    }).sort(function (a, b) {
        return sort(a, b, inputValue);
    });
    if (filtered.length > 0) {
        return filtered.map(function (path) {
            return {
                __IS_FILTERED_OPTION: true,
                path: path,
                label: render(inputValue, path, prefixCls),
                value: path.map(function (o) {
                    return o.value;
                }),
                disabled: path.some(function (o) {
                    return o.disabled;
                })
            };
        });
    }
    return [{ label: notFoundContent, value: 'ANT_CASCADER_NOT_FOUND', disabled: true }];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Cascader.prototype.getLabel"></a>[function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>getLabel ()](#apidoc.element.antd.Cascader.prototype.getLabel)
- description and source-code
```javascript
function getLabel() {
    var _props = this.props,
        options = _props.options,
        _props$displayRender = _props.displayRender,
        displayRender = _props$displayRender === undefined ? defaultDisplayRender : _props$displayRender;

    var value = this.state.value;
    var unwrappedValue = Array.isArray(value[0]) ? value[0] : value;
    var selectedOptions = (0, _arrayTreeFilter2["default"])(options, function (o, level) {
        return o.value === unwrappedValue[level];
    });
    var label = selectedOptions.map(function (o) {
        return o.label;
    });
    return displayRender(label, selectedOptions);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Cascader.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Cascader.prototype.</span>render ()](#apidoc.element.antd.Cascader.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames, _classNames2, _classNames3;

    var props = this.props,
        state = this.state;

    var prefixCls = props.prefixCls,
        inputPrefixCls = props.inputPrefixCls,
        children = props.children,
        placeholder = props.placeholder,
        size = props.size,
        disabled = props.disabled,
        className = props.className,
        style = props.style,
        allowClear = props.allowClear,
        _props$showSearch = props.showSearch,
        showSearch = _props$showSearch === undefined ? false : _props$showSearch,
        otherProps = __rest(props, ["prefixCls", "inputPrefixCls", "children", "placeholder", "size", "disabled", "className", "
style", "allowClear", "showSearch"]);

    var value = state.value;
    var sizeCls = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, inputPrefixCls + '-
lg', size === 'large'), (0, _defineProperty3["default"])(_classNames, inputPrefixCls + '-sm', size === 'small'), _classNames));
    var clearIcon = allowClear && !disabled && value.length > 0 || state.inputValue ? _react2["default"].createElement(_icon2["default
"], { type: 'cross-circle', className: prefixCls + '-picker-clear', onClick: this.clearSelection }) : null;
    var arrowCls = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2, prefixCls + '-
picker-arrow', true), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-picker-arrow-expand', state.popupVisible), _classNames2
));
    var pickerCls = (0, _classnames2["default"])(className, (_classNames3 = {}, (0, _defineProperty3["default"])(_classNames3, prefixCls
 + '-picker', true), (0, _defineProperty3["default"])(_classNames3, prefixCls + '-picker-with-value', state.inputValue), (0, _defineProperty3
["default"])(_classNames3, prefixCls + '-picker-disabled', disabled), _classNames3));
    // Fix bug of https://github.com/facebook/react/pull/5004
    // and https://fb.me/react-unknown-prop
    var inputProps = (0, _omit2["default"])(otherProps, ['onChange', 'options', 'popupPlacement', 'transitionName', 'displayRender
', 'onPopupVisibleChange', 'changeOnSelect', 'expandTrigger', 'popupVisible', 'getPopupContainer', 'loadData', 'popupClassName', '
filterOption', 'renderFilteredOption', 'sortFilteredOption', 'notFoundContent']);
    var options = props.options;
    if (state.inputValue) {
        options = this.generateFilteredOptions(prefixCls);
    }
    // Dropdown menu should keep previous status until it is fully closed.
    if (!state.popupVisible) {
        options = this.cachedOptions;
    } else {
        this.cachedOptions = options;
    }
    var dropdownMenuColumnStyle = {};
    var isNotFound = (options || []).length === 1 && options[0].value === 'ANT_CASCADER_NOT_FOUND';
    if (isNotFound) {
        dropdownMenuColumnStyle.height = 'auto'; // Height of one row.
    }
    // The default value of 'matchInputWidth' is 'true'
    var resultListMatchInputWidth = showSearch.matchInputWidth === false ? false : true;
    if (resultListMatchInputWidth && state.inputValue && this.refs.input) {
        dropdownMenuColumnStyle.width = this.refs.input.refs.input.offsetWidth;
    }
    var input = children || _react2["default"].createElement(
        'span',
        { style: style, className: pickerCls },
        _react2["default"].createElement(_input2["default"], (0, _extends3["default"])({}, inputProps, { ref: 'input', placeholder
: value && value.length > 0 ? undefined : placeholder, className: prefixCls + '-input ' + sizeCls, value: state.inputValue, disabled
: disabled, readOnly: !showSearch, autoComplete: 'off', onClick: showSearch ? this.handleInputClick : undefined, onBlur: showSearch
 ? this.handleInputBlur : undefined, onKeyDown: this.handleKeyDown, onChange: showSearch ? this.handleInputChange : undefined })),
        _react2["default"].createElement(
            'span',
            { className: prefixCls + '-picker-label' },
            this.getLabel()
        ),
        clearIcon,
        _react2["default"] ...
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Checkbox"></a>[module antd.Checkbox](#apidoc.module.antd.Checkbox)

#### <a name="apidoc.element.antd.Checkbox.Checkbox"></a>[function <span class="apidocSignatureSpan">antd.</span>Checkbox ()](#apidoc.element.antd.Checkbox.Checkbox)
- description and source-code
```javascript
function Checkbox() {
    (0, _classCallCheck3["default"])(this, Checkbox);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Checkbox.Group"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.</span>Group (props)](#apidoc.element.antd.Checkbox.Group)
- description and source-code
```javascript
function CheckboxGroup(props) {
    (0, _classCallCheck3["default"])(this, CheckboxGroup);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.toggleOption = function (option) {
        var optionIndex = _this.state.value.indexOf(option.value);
        var value = [].concat((0, _toConsumableArray3["default"])(_this.state.value));
        if (optionIndex === -1) {
            value.push(option.value);
        } else {
            value.splice(optionIndex, 1);
        }
        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(value);
        }
    };
    _this.state = {
        value: props.value || props.defaultValue || []
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Checkbox.Group"></a>[module antd.Checkbox.Group](#apidoc.module.antd.Checkbox.Group)

#### <a name="apidoc.element.antd.Checkbox.Group.Group"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.</span>Group (props)](#apidoc.element.antd.Checkbox.Group.Group)
- description and source-code
```javascript
function CheckboxGroup(props) {
    (0, _classCallCheck3["default"])(this, CheckboxGroup);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.toggleOption = function (option) {
        var optionIndex = _this.state.value.indexOf(option.value);
        var value = [].concat((0, _toConsumableArray3["default"])(_this.state.value));
        if (optionIndex === -1) {
            value.push(option.value);
        } else {
            value.splice(optionIndex, 1);
        }
        if (!('value' in _this.props)) {
            _this.setState({ value: value });
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(value);
        }
    };
    _this.state = {
        value: props.value || props.defaultValue || []
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Checkbox.Group.prototype"></a>[module antd.Checkbox.Group.prototype](#apidoc.module.antd.Checkbox.Group.prototype)

#### <a name="apidoc.element.antd.Checkbox.Group.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Checkbox.Group.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('value' in nextProps) {
        this.setState({
            value: nextProps.value || []
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Checkbox.Group.prototype.getOptions"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>getOptions ()](#apidoc.element.antd.Checkbox.Group.prototype.getOptions)
- description and source-code
```javascript
function getOptions() {
    var options = this.props.options;
    // https://github.com/Microsoft/TypeScript/issues/7960

    return options.map(function (option) {
        if (typeof option === 'string') {
            return {
                label: option,
                value: option
            };
        }
        return option;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Checkbox.Group.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>render ()](#apidoc.element.antd.Checkbox.Group.prototype.render)
- description and source-code
```javascript
function render() {
    var _this2 = this;

    var _props = this.props,
        prefixCls = _props.prefixCls,
        className = _props.className;

    var options = this.getOptions().map(function (option) {
        return _react2["default"].createElement(
            _Checkbox2["default"],
            { disabled: 'disabled' in option ? option.disabled : _this2.props.disabled, checked: _this2.state.value.indexOf(option
.value) !== -1, onChange: function onChange() {
                    return _this2.toggleOption(option);
                }, className: prefixCls + '-item', key: option.value },
            option.label
        );
    });
    var classString = (0, _classnames2["default"])(prefixCls, className);
    return _react2["default"].createElement(
        'div',
        { className: classString },
        options
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Checkbox.Group.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.Group.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Checkbox.Group.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
    for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
    }

    return _PureRenderMixin2["default"].shouldComponentUpdate.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Checkbox.prototype"></a>[module antd.Checkbox.prototype](#apidoc.module.antd.Checkbox.prototype)

#### <a name="apidoc.element.antd.Checkbox.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.prototype.</span>render ()](#apidoc.element.antd.Checkbox.prototype.render)
- description and source-code
```javascript
function render() {
    var _a = this.props,
        prefixCls = _a.prefixCls,
        style = _a.style,
        children = _a.children,
        className = _a.className,
        indeterminate = _a.indeterminate,
        onMouseEnter = _a.onMouseEnter,
        onMouseLeave = _a.onMouseLeave,
        restProps = __rest(_a, ["prefixCls", "style", "children", "className", "indeterminate", "onMouseEnter", "onMouseLeave"]);
    var classString = (0, _classnames2["default"])(className, (0, _defineProperty3["default"])({}, prefixCls + '-wrapper', true));
    var checkboxClass = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-indeterminate', indeterminate
));
    return _react2["default"].createElement(
        'label',
        { className: classString, style: style, onMouseEnter: onMouseEnter, onMouseLeave: onMouseLeave },
        _react2["default"].createElement(_rcCheckbox2["default"], (0, _extends3["default"])({}, restProps, { prefixCls: prefixCls
, className: checkboxClass, children: null })),
        children !== undefined ? _react2["default"].createElement(
            'span',
            null,
            children
        ) : null
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Checkbox.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">antd.Checkbox.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Checkbox.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
    for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
    }

    return _PureRenderMixin2["default"].shouldComponentUpdate.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Col"></a>[module antd.Col](#apidoc.module.antd.Col)

#### <a name="apidoc.element.antd.Col.Col"></a>[function <span class="apidocSignatureSpan">antd.</span>Col ()](#apidoc.element.antd.Col.Col)
- description and source-code
```javascript
function Col() {
    (0, _classCallCheck3["default"])(this, Col);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Col.propTypes"></a>[module antd.Col.propTypes](#apidoc.module.antd.Col.propTypes)

#### <a name="apidoc.element.antd.Col.propTypes.children"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>children ()](#apidoc.element.antd.Col.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>className ()](#apidoc.element.antd.Col.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.lg"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>lg ()](#apidoc.element.antd.Col.propTypes.lg)
- description and source-code
```javascript
lg = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.md"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>md ()](#apidoc.element.antd.Col.propTypes.md)
- description and source-code
```javascript
md = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.offset"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>offset ()](#apidoc.element.antd.Col.propTypes.offset)
- description and source-code
```javascript
offset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.order"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>order ()](#apidoc.element.antd.Col.propTypes.order)
- description and source-code
```javascript
order = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.pull"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>pull ()](#apidoc.element.antd.Col.propTypes.pull)
- description and source-code
```javascript
pull = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.push"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>push ()](#apidoc.element.antd.Col.propTypes.push)
- description and source-code
```javascript
push = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.sm"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>sm ()](#apidoc.element.antd.Col.propTypes.sm)
- description and source-code
```javascript
sm = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.span"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>span ()](#apidoc.element.antd.Col.propTypes.span)
- description and source-code
```javascript
span = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.xl"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>xl ()](#apidoc.element.antd.Col.propTypes.xl)
- description and source-code
```javascript
xl = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Col.propTypes.xs"></a>[function <span class="apidocSignatureSpan">antd.Col.propTypes.</span>xs ()](#apidoc.element.antd.Col.propTypes.xs)
- description and source-code
```javascript
xs = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Col.prototype"></a>[module antd.Col.prototype](#apidoc.module.antd.Col.prototype)

#### <a name="apidoc.element.antd.Col.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Col.prototype.</span>render ()](#apidoc.element.antd.Col.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var props = this.props;

    var span = props.span,
        order = props.order,
        offset = props.offset,
        push = props.push,
        pull = props.pull,
        className = props.className,
        children = props.children,
        _props$prefixCls = props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? 'ant-col' : _props$prefixCls,
        others = __rest(props, ["span", "order", "offset", "push", "pull", "className", "children", "prefixCls"]);

    var sizeClassObj = {};
    ['xs', 'sm', 'md', 'lg', 'xl'].forEach(function (size) {
        var _assign;

        var sizeProps = {};
        if (typeof props[size] === 'number') {
            sizeProps.span = props[size];
        } else if ((0, _typeof3["default"])(props[size]) === 'object') {
            sizeProps = props[size] || {};
        }
        delete others[size];
        sizeClassObj = (0, _objectAssign2["default"])({}, sizeClassObj, (_assign = {}, (0, _defineProperty3["default"])(_assign,
prefixCls + '-' + size + '-' + sizeProps.span, sizeProps.span !== undefined), (0, _defineProperty3["default"])(_assign, prefixCls
 + '-' + size + '-order-' + sizeProps.order, sizeProps.order || sizeProps.order === 0), (0, _defineProperty3["default"])(_assign
, prefixCls + '-' + size + '-offset-' + sizeProps.offset, sizeProps.offset || sizeProps.offset === 0), (0, _defineProperty3["default
"])(_assign, prefixCls + '-' + size + '-push-' + sizeProps.push, sizeProps.push || sizeProps.push === 0), (0, _defineProperty3["
default"])(_assign, prefixCls + '-' + size + '-pull-' + sizeProps.pull, sizeProps.pull || sizeProps.pull === 0), _assign));
    });
    var classes = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls + '-' +
span, span !== undefined), (0, _defineProperty3["default"])(_classNames, prefixCls + '-order-' + order, order), (0, _defineProperty3
["default"])(_classNames, prefixCls + '-offset-' + offset, offset), (0, _defineProperty3["default"])(_classNames, prefixCls + '-
push-' + push, push), (0, _defineProperty3["default"])(_classNames, prefixCls + '-pull-' + pull, pull), _classNames), className,
sizeClassObj);
    return _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({}, others, { className: classes }),
        children
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Collapse"></a>[module antd.Collapse](#apidoc.module.antd.Collapse)

#### <a name="apidoc.element.antd.Collapse.Collapse"></a>[function <span class="apidocSignatureSpan">antd.</span>Collapse ()](#apidoc.element.antd.Collapse.Collapse)
- description and source-code
```javascript
function Collapse() {
    (0, _classCallCheck3["default"])(this, Collapse);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component2.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel"></a>[function <span class="apidocSignatureSpan">antd.Collapse.</span>Panel (props, context, updater)](#apidoc.element.antd.Collapse.Panel)
- description and source-code
```javascript
Panel = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Collapse.Panel"></a>[module antd.Collapse.Panel](#apidoc.module.antd.Collapse.Panel)

#### <a name="apidoc.element.antd.Collapse.Panel.Panel"></a>[function <span class="apidocSignatureSpan">antd.Collapse.</span>Panel (props, context, updater)](#apidoc.element.antd.Collapse.Panel.Panel)
- description and source-code
```javascript
Panel = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.</span>getDefaultProps ()](#apidoc.element.antd.Collapse.Panel.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    showArrow: true,
    isActive: false,
    onItemClick: function onItemClick() {}
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Collapse.Panel.prototype"></a>[module antd.Collapse.Panel.prototype](#apidoc.module.antd.Collapse.Panel.prototype)

#### <a name="apidoc.element.antd.Collapse.Panel.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Collapse.Panel.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>getDOMNode ()](#apidoc.element.antd.Collapse.Panel.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel.prototype.handleItemClick"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>handleItemClick ()](#apidoc.element.antd.Collapse.Panel.prototype.handleItemClick)
- description and source-code
```javascript
function handleItemClick() {
  this.props.onItemClick();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.</span>render ()](#apidoc.element.antd.Collapse.Panel.prototype.render)
- description and source-code
```javascript
function render() {
  var _classNames;

  var _props = this.props,
      className = _props.className,
      style = _props.style,
      prefixCls = _props.prefixCls,
      header = _props.header,
      children = _props.children,
      isActive = _props.isActive,
      showArrow = _props.showArrow;

  var headerCls = prefixCls + '-header';
  var itemCls = (0, _classnames2["default"])((_classNames = {}, _defineProperty(_classNames, prefixCls + '-item', true), _defineProperty
(_classNames, prefixCls + '-item-active', isActive), _classNames), className);
  return _react2["default"].createElement(
    'div',
    { className: itemCls, style: style },
    _react2["default"].createElement(
      'div',
      {
        className: headerCls,
        onClick: this.handleItemClick,
        role: 'tab',
        'aria-expanded': isActive
      },
      showArrow && _react2["default"].createElement('i', { className: 'arrow' }),
      header
    ),
    _react2["default"].createElement(
      _rcAnimate2["default"],
      {
        showProp: 'isActive',
        exclusive: true,
        component: '',
        animation: this.props.openAnimation
      },
      _react2["default"].createElement(
        _PanelContent2["default"],
        { prefixCls: prefixCls, isActive: isActive },
        children
      )
    )
  );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Collapse.Panel.prototype.__reactAutoBindMap"></a>[module antd.Collapse.Panel.prototype.__reactAutoBindMap](#apidoc.module.antd.Collapse.Panel.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.Collapse.Panel.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Collapse.Panel.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Collapse.Panel.prototype.__reactAutoBindMap.handleItemClick"></a>[function <span class="apidocSignatureSpan">antd.Collapse.Panel.prototype.__reactAutoBindMap.</span>handleItemClick ()](#apidoc.element.antd.Collapse.Panel.prototype.__reactAutoBindMap.handleItemClick)
- description and source-code
```javascript
function handleItemClick() {
  this.props.onItemClick();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Collapse.prototype"></a>[module antd.Collapse.prototype](#apidoc.module.antd.Collapse.prototype)

#### <a name="apidoc.element.antd.Collapse.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Collapse.prototype.</span>render ()](#apidoc.element.antd.Collapse.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        prefixCls = _props.prefixCls,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        bordered = _props.bordered;

    var collapseClassName = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-borderless', !bordered
), className);
    return _react2["default"].createElement(_rcCollapse2["default"], (0, _extends3["default"])({}, this.props, { className: collapseClassName
 }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.DatePicker"></a>[module antd.DatePicker](#apidoc.module.antd.DatePicker)

#### <a name="apidoc.element.antd.DatePicker.DatePicker"></a>[function <span class="apidocSignatureSpan">antd.</span>DatePicker (props, context, updater)](#apidoc.element.antd.DatePicker.DatePicker)
- description and source-code
```javascript
DatePicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.Calendar"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>Calendar ()](#apidoc.element.antd.DatePicker.Calendar)
- description and source-code
```javascript
function Calendar() {
    (0, _classCallCheck3["default"])(this, Calendar);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>MonthPicker (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker)
- description and source-code
```javascript
MonthPicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>RangePicker (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker)
- description and source-code
```javascript
RangePicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>getDefaultProps ()](#apidoc.element.antd.DatePicker.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
    return {
        format: defaultFormat || 'YYYY-MM-DD',
        transitionName: 'slide-up',
        popupStyle: {},
        onChange: function onChange() {},
        onOk: function onOk() {},
        onOpenChange: function onOpenChange() {},

        locale: {},
        align: {
            offset: [0, -9]
        },
        prefixCls: 'ant-calendar',
        inputPrefixCls: 'ant-input'
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.Calendar"></a>[module antd.DatePicker.Calendar](#apidoc.module.antd.DatePicker.Calendar)

#### <a name="apidoc.element.antd.DatePicker.Calendar.Calendar"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>Calendar ()](#apidoc.element.antd.DatePicker.Calendar.Calendar)
- description and source-code
```javascript
function Calendar() {
    (0, _classCallCheck3["default"])(this, Calendar);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.Calendar.prototype"></a>[module antd.DatePicker.Calendar.prototype](#apidoc.module.antd.DatePicker.Calendar.prototype)

#### <a name="apidoc.element.antd.DatePicker.Calendar.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.Calendar.prototype.</span>render ()](#apidoc.element.antd.DatePicker.Calendar.prototype.render)
- description and source-code
```javascript
function render() {
    (0, _warning2["default"])(false, 'DatePicker.Calendar is deprecated, use Calendar instead.');
    return _react2["default"].createElement(_rcCalendar2["default"], this.props);
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.DatePicker.MonthPicker"></a>[module antd.DatePicker.MonthPicker](#apidoc.module.antd.DatePicker.MonthPicker)

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.MonthPicker"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>MonthPicker (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker.MonthPicker)
- description and source-code
```javascript
MonthPicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.</span>getDefaultProps ()](#apidoc.element.antd.DatePicker.MonthPicker.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
    return {
        format: defaultFormat || 'YYYY-MM-DD',
        transitionName: 'slide-up',
        popupStyle: {},
        onChange: function onChange() {},
        onOk: function onOk() {},
        onOpenChange: function onOpenChange() {},

        locale: {},
        align: {
            offset: [0, -9]
        },
        prefixCls: 'ant-calendar',
        inputPrefixCls: 'ant-input'
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.MonthPicker.prototype"></a>[module antd.DatePicker.MonthPicker.prototype](#apidoc.module.antd.DatePicker.MonthPicker.prototype)

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.DatePicker.MonthPicker.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.MonthPicker.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.prototype.handleOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.MonthPicker.prototype.handleOpenChange)
- description and source-code
```javascript
function handleOpenChange(open) {
    var _props = this.props,
        onOpenChange = _props.onOpenChange,
        toggleOpen = _props.toggleOpen;

    onOpenChange(open);
    if (toggleOpen) {
        (0, _warning2["default"])(false, ''toggleOpen' is deprecated and will be removed in the future, ' + 'please use 'onOpenChange
' instead, see: http://u.ant.design/date-picker-on-open-change');
        toggleOpen({ open: open });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.</span>render ()](#apidoc.element.antd.DatePicker.MonthPicker.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames2, _classNames3;

    var props = this.props;
    var prefixCls = props.prefixCls,
        inputPrefixCls = props.inputPrefixCls;

    var pickerClass = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-picker', true));
    var pickerInputClass = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2, prefixCls
 + '-picker-input', true), (0, _defineProperty3["default"])(_classNames2, inputPrefixCls, true), (0, _defineProperty3["default"])(
_classNames2, inputPrefixCls + '-lg', props.size === 'large'), (0, _defineProperty3["default"])(_classNames2, inputPrefixCls + '-
sm', props.size === 'small'), _classNames2));
    var locale = (0, _getLocale.getComponentLocale)(props, this.context, 'DatePicker', function () {
        return require('./locale/zh_CN');
    });
    var timeFormat = props.showTime && props.showTime.format || 'HH:mm:ss';
    var rcTimePickerProps = {
        format: timeFormat,
        showSecond: timeFormat.indexOf('ss') >= 0,
        showMinute: timeFormat.indexOf('mm') >= 0,
        showHour: timeFormat.indexOf('HH') >= 0
    };
    var columns = getColumns(rcTimePickerProps);
    var timePickerCls = (0, _classnames2["default"])((_classNames3 = {}, (0, _defineProperty3["default"])(_classNames3, prefixCls
 + '-time-picker-1-column', columns === 1), (0, _defineProperty3["default"])(_classNames3, prefixCls + '-time-picker-2-columns',
columns === 2), _classNames3));
    var timePicker = props.showTime ? _react2["default"].createElement(_Panel2["default"], (0, _extends3["default"])({}, rcTimePickerProps
, props.showTime, { prefixCls: prefixCls + '-time-picker', className: timePickerCls, placeholder: locale.timePickerLocale.placeholder
, transitionName: 'slide-up' })) : null;
    return _react2["default"].createElement(Picker, (0, _extends3["default"])({}, props, { pickerClass: pickerClass, pickerInputClass
: pickerInputClass, locale: locale, timePicker: timePicker, onOpenChange: this.handleOpenChange }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap"></a>[module antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap](#apidoc.module.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.handleOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.MonthPicker.prototype.__reactAutoBindMap.handleOpenChange)
- description and source-code
```javascript
function handleOpenChange(open) {
    var _props = this.props,
        onOpenChange = _props.onOpenChange,
        toggleOpen = _props.toggleOpen;

    onOpenChange(open);
    if (toggleOpen) {
        (0, _warning2["default"])(false, ''toggleOpen' is deprecated and will be removed in the future, ' + 'please use 'onOpenChange
' instead, see: http://u.ant.design/date-picker-on-open-change');
        toggleOpen({ open: open });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.RangePicker"></a>[module antd.DatePicker.RangePicker](#apidoc.module.antd.DatePicker.RangePicker)

#### <a name="apidoc.element.antd.DatePicker.RangePicker.RangePicker"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.</span>RangePicker (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker.RangePicker)
- description and source-code
```javascript
RangePicker = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.</span>getDefaultProps ()](#apidoc.element.antd.DatePicker.RangePicker.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
    return {
        format: defaultFormat || 'YYYY-MM-DD',
        transitionName: 'slide-up',
        popupStyle: {},
        onChange: function onChange() {},
        onOk: function onOk() {},
        onOpenChange: function onOpenChange() {},

        locale: {},
        align: {
            offset: [0, -9]
        },
        prefixCls: 'ant-calendar',
        inputPrefixCls: 'ant-input'
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.RangePicker.prototype"></a>[module antd.DatePicker.RangePicker.prototype](#apidoc.module.antd.DatePicker.RangePicker.prototype)

#### <a name="apidoc.element.antd.DatePicker.RangePicker.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.DatePicker.RangePicker.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.RangePicker.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker.prototype.handleOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.RangePicker.prototype.handleOpenChange)
- description and source-code
```javascript
function handleOpenChange(open) {
    var _props = this.props,
        onOpenChange = _props.onOpenChange,
        toggleOpen = _props.toggleOpen;

    onOpenChange(open);
    if (toggleOpen) {
        (0, _warning2["default"])(false, ''toggleOpen' is deprecated and will be removed in the future, ' + 'please use 'onOpenChange
' instead, see: http://u.ant.design/date-picker-on-open-change');
        toggleOpen({ open: open });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.</span>render ()](#apidoc.element.antd.DatePicker.RangePicker.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames2, _classNames3;

    var props = this.props;
    var prefixCls = props.prefixCls,
        inputPrefixCls = props.inputPrefixCls;

    var pickerClass = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-picker', true));
    var pickerInputClass = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2, prefixCls
 + '-picker-input', true), (0, _defineProperty3["default"])(_classNames2, inputPrefixCls, true), (0, _defineProperty3["default"])(
_classNames2, inputPrefixCls + '-lg', props.size === 'large'), (0, _defineProperty3["default"])(_classNames2, inputPrefixCls + '-
sm', props.size === 'small'), _classNames2));
    var locale = (0, _getLocale.getComponentLocale)(props, this.context, 'DatePicker', function () {
        return require('./locale/zh_CN');
    });
    var timeFormat = props.showTime && props.showTime.format || 'HH:mm:ss';
    var rcTimePickerProps = {
        format: timeFormat,
        showSecond: timeFormat.indexOf('ss') >= 0,
        showMinute: timeFormat.indexOf('mm') >= 0,
        showHour: timeFormat.indexOf('HH') >= 0
    };
    var columns = getColumns(rcTimePickerProps);
    var timePickerCls = (0, _classnames2["default"])((_classNames3 = {}, (0, _defineProperty3["default"])(_classNames3, prefixCls
 + '-time-picker-1-column', columns === 1), (0, _defineProperty3["default"])(_classNames3, prefixCls + '-time-picker-2-columns',
columns === 2), _classNames3));
    var timePicker = props.showTime ? _react2["default"].createElement(_Panel2["default"], (0, _extends3["default"])({}, rcTimePickerProps
, props.showTime, { prefixCls: prefixCls + '-time-picker', className: timePickerCls, placeholder: locale.timePickerLocale.placeholder
, transitionName: 'slide-up' })) : null;
    return _react2["default"].createElement(Picker, (0, _extends3["default"])({}, props, { pickerClass: pickerClass, pickerInputClass
: pickerInputClass, locale: locale, timePicker: timePicker, onOpenChange: this.handleOpenChange }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap"></a>[module antd.DatePicker.RangePicker.prototype.__reactAutoBindMap](#apidoc.module.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.handleOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.RangePicker.prototype.__reactAutoBindMap.handleOpenChange)
- description and source-code
```javascript
function handleOpenChange(open) {
    var _props = this.props,
        onOpenChange = _props.onOpenChange,
        toggleOpen = _props.toggleOpen;

    onOpenChange(open);
    if (toggleOpen) {
        (0, _warning2["default"])(false, ''toggleOpen' is deprecated and will be removed in the future, ' + 'please use 'onOpenChange
' instead, see: http://u.ant.design/date-picker-on-open-change');
        toggleOpen({ open: open });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.contextTypes"></a>[module antd.DatePicker.contextTypes](#apidoc.module.antd.DatePicker.contextTypes)

#### <a name="apidoc.element.antd.DatePicker.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.contextTypes.</span>antLocale ()](#apidoc.element.antd.DatePicker.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.defaultProps"></a>[module antd.DatePicker.defaultProps](#apidoc.module.antd.DatePicker.defaultProps)

#### <a name="apidoc.element.antd.DatePicker.defaultProps.onChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>onChange ()](#apidoc.element.antd.DatePicker.defaultProps.onChange)
- description and source-code
```javascript
function onChange() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.defaultProps.onOk"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>onOk ()](#apidoc.element.antd.DatePicker.defaultProps.onOk)
- description and source-code
```javascript
function onOk() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.defaultProps.onOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.defaultProps.</span>onOpenChange ()](#apidoc.element.antd.DatePicker.defaultProps.onOpenChange)
- description and source-code
```javascript
function onOpenChange() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.DatePicker.prototype"></a>[module antd.DatePicker.prototype](#apidoc.module.antd.DatePicker.prototype)

#### <a name="apidoc.element.antd.DatePicker.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.DatePicker.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.prototype.handleOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.prototype.handleOpenChange)
- description and source-code
```javascript
function handleOpenChange(open) {
    var _props = this.props,
        onOpenChange = _props.onOpenChange,
        toggleOpen = _props.toggleOpen;

    onOpenChange(open);
    if (toggleOpen) {
        (0, _warning2["default"])(false, ''toggleOpen' is deprecated and will be removed in the future, ' + 'please use 'onOpenChange
' instead, see: http://u.ant.design/date-picker-on-open-change');
        toggleOpen({ open: open });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.prototype.</span>render ()](#apidoc.element.antd.DatePicker.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames2, _classNames3;

    var props = this.props;
    var prefixCls = props.prefixCls,
        inputPrefixCls = props.inputPrefixCls;

    var pickerClass = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-picker', true));
    var pickerInputClass = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2, prefixCls
 + '-picker-input', true), (0, _defineProperty3["default"])(_classNames2, inputPrefixCls, true), (0, _defineProperty3["default"])(
_classNames2, inputPrefixCls + '-lg', props.size === 'large'), (0, _defineProperty3["default"])(_classNames2, inputPrefixCls + '-
sm', props.size === 'small'), _classNames2));
    var locale = (0, _getLocale.getComponentLocale)(props, this.context, 'DatePicker', function () {
        return require('./locale/zh_CN');
    });
    var timeFormat = props.showTime && props.showTime.format || 'HH:mm:ss';
    var rcTimePickerProps = {
        format: timeFormat,
        showSecond: timeFormat.indexOf('ss') >= 0,
        showMinute: timeFormat.indexOf('mm') >= 0,
        showHour: timeFormat.indexOf('HH') >= 0
    };
    var columns = getColumns(rcTimePickerProps);
    var timePickerCls = (0, _classnames2["default"])((_classNames3 = {}, (0, _defineProperty3["default"])(_classNames3, prefixCls
 + '-time-picker-1-column', columns === 1), (0, _defineProperty3["default"])(_classNames3, prefixCls + '-time-picker-2-columns',
columns === 2), _classNames3));
    var timePicker = props.showTime ? _react2["default"].createElement(_Panel2["default"], (0, _extends3["default"])({}, rcTimePickerProps
, props.showTime, { prefixCls: prefixCls + '-time-picker', className: timePickerCls, placeholder: locale.timePickerLocale.placeholder
, transitionName: 'slide-up' })) : null;
    return _react2["default"].createElement(Picker, (0, _extends3["default"])({}, props, { pickerClass: pickerClass, pickerInputClass
: pickerInputClass, locale: locale, timePicker: timePicker, onOpenChange: this.handleOpenChange }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.DatePicker.prototype.__reactAutoBindMap"></a>[module antd.DatePicker.prototype.__reactAutoBindMap](#apidoc.module.antd.DatePicker.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.DatePicker.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.DatePicker.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.DatePicker.prototype.__reactAutoBindMap.handleOpenChange"></a>[function <span class="apidocSignatureSpan">antd.DatePicker.prototype.__reactAutoBindMap.</span>handleOpenChange (open)](#apidoc.element.antd.DatePicker.prototype.__reactAutoBindMap.handleOpenChange)
- description and source-code
```javascript
function handleOpenChange(open) {
    var _props = this.props,
        onOpenChange = _props.onOpenChange,
        toggleOpen = _props.toggleOpen;

    onOpenChange(open);
    if (toggleOpen) {
        (0, _warning2["default"])(false, ''toggleOpen' is deprecated and will be removed in the future, ' + 'please use 'onOpenChange
' instead, see: http://u.ant.design/date-picker-on-open-change');
        toggleOpen({ open: open });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Dropdown"></a>[module antd.Dropdown](#apidoc.module.antd.Dropdown)

#### <a name="apidoc.element.antd.Dropdown.Dropdown"></a>[function <span class="apidocSignatureSpan">antd.</span>Dropdown ()](#apidoc.element.antd.Dropdown.Dropdown)
- description and source-code
```javascript
function Dropdown() {
    (0, _classCallCheck3["default"])(this, Dropdown);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Dropdown.Button"></a>[function <span class="apidocSignatureSpan">antd.Dropdown.</span>Button ()](#apidoc.element.antd.Dropdown.Button)
- description and source-code
```javascript
function DropdownButton() {
    (0, _classCallCheck3["default"])(this, DropdownButton);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Dropdown.Button"></a>[module antd.Dropdown.Button](#apidoc.module.antd.Dropdown.Button)

#### <a name="apidoc.element.antd.Dropdown.Button.Button"></a>[function <span class="apidocSignatureSpan">antd.Dropdown.</span>Button ()](#apidoc.element.antd.Dropdown.Button.Button)
- description and source-code
```javascript
function DropdownButton() {
    (0, _classCallCheck3["default"])(this, DropdownButton);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Dropdown.Button.prototype"></a>[module antd.Dropdown.Button.prototype](#apidoc.module.antd.Dropdown.Button.prototype)

#### <a name="apidoc.element.antd.Dropdown.Button.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Dropdown.Button.prototype.</span>render ()](#apidoc.element.antd.Dropdown.Button.prototype.render)
- description and source-code
```javascript
function render() {
    var _a = this.props,
        type = _a.type,
        overlay = _a.overlay,
        trigger = _a.trigger,
        align = _a.align,
        children = _a.children,
        className = _a.className,
        onClick = _a.onClick,
        prefixCls = _a.prefixCls,
        disabled = _a.disabled,
        visible = _a.visible,
        onVisibleChange = _a.onVisibleChange,
        placement = _a.placement,
        restProps = __rest(_a, ["type", "overlay", "trigger", "align", "children", "className", "onClick", "prefixCls", "disabled
", "visible", "onVisibleChange", "placement"]);
    var cls = (0, _classnames2["default"])(prefixCls, className);
    var dropdownProps = {
        align: align,
        overlay: overlay,
        trigger: disabled ? [] : trigger,
        onVisibleChange: onVisibleChange,
        placement: placement
    };
    if ('visible' in this.props) {
        dropdownProps.visible = visible;
    }
    return _react2["default"].createElement(
        ButtonGroup,
        (0, _extends3["default"])({}, restProps, { className: cls }),
        _react2["default"].createElement(
            _button2["default"],
            { type: type, onClick: onClick, disabled: disabled },
            children
        ),
        _react2["default"].createElement(
            _dropdown2["default"],
            dropdownProps,
            _react2["default"].createElement(
                _button2["default"],
                { type: type, disabled: disabled },
                _react2["default"].createElement(_icon2["default"], { type: 'down' })
            )
        )
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Dropdown.prototype"></a>[module antd.Dropdown.prototype](#apidoc.module.antd.Dropdown.prototype)

#### <a name="apidoc.element.antd.Dropdown.prototype.getTransitionName"></a>[function <span class="apidocSignatureSpan">antd.Dropdown.prototype.</span>getTransitionName ()](#apidoc.element.antd.Dropdown.prototype.getTransitionName)
- description and source-code
```javascript
function getTransitionName() {
    var _props$placement = this.props.placement,
        placement = _props$placement === undefined ? '' : _props$placement;

    if (placement.indexOf('top') >= 0) {
        return 'slide-down';
    }
    return 'slide-up';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Dropdown.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Dropdown.prototype.</span>render ()](#apidoc.element.antd.Dropdown.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        children = _props.children,
        prefixCls = _props.prefixCls;

    var dropdownTrigger = (0, _react.cloneElement)(children, {
        className: (0, _classnames2["default"])(children.props.className, prefixCls + '-trigger')
    });
    return _react2["default"].createElement(
        _rcDropdown2["default"],
        (0, _extends3["default"])({ transitionName: this.getTransitionName() }, this.props),
        dropdownTrigger
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Form"></a>[module antd.Form](#apidoc.module.antd.Form)

#### <a name="apidoc.element.antd.Form.Form"></a>[function <span class="apidocSignatureSpan">antd.</span>Form (props)](#apidoc.element.antd.Form.Form)
- description and source-code
```javascript
function Form(props) {
    (0, _classCallCheck3["default"])(this, Form);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    (0, _warning2["default"])(!props.form, 'It is unnecessary to pass 'form' to 'Form' after antd@1.7.0.');
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item"></a>[function <span class="apidocSignatureSpan">antd.Form.</span>Item ()](#apidoc.element.antd.Form.Item)
- description and source-code
```javascript
function FormItem() {
    (0, _classCallCheck3["default"])(this, FormItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.create"></a>[function <span class="apidocSignatureSpan">antd.Form.</span>create (options)](#apidoc.element.antd.Form.create)
- description and source-code
```javascript
create = function (options) {
    var formWrapper = (0, _createDOMForm2["default"])((0, _objectAssign2["default"])({
        fieldNameProp: 'id'
    }, options, {
        fieldMetaProp: _constants.FIELD_META_PROP
    }));
<span class="apidocCodeCommentSpan">    /* eslint-disable react/prefer-es6-class */
</span>    return function (Component) {
        return formWrapper(_react2["default"].createClass({
            propTypes: {
                form: _react.PropTypes.object.isRequired
            },
            childContextTypes: {
                form: _react.PropTypes.object.isRequired
            },
            getChildContext: function getChildContext() {
                return {
                    form: this.props.form
                };
            },
            componentWillMount: function componentWillMount() {
                this.__getFieldProps = this.props.form.getFieldProps;
            },
            deprecatedGetFieldProps: function deprecatedGetFieldProps(name, option) {
                (0, _warning2["default"])(false, ''getFieldProps' is not recommended, please use 'getFieldDecorator' instead, ' + '
see: http://u.ant.design/get-field-decorator');
                return this.__getFieldProps(name, option);
            },
            render: function render() {
                this.props.form.getFieldProps = this.deprecatedGetFieldProps;
                var withRef = {};
                if (options && options.withRef) {
                    withRef.ref = 'formWrappedComponent';
                }
                return _react2["default"].createElement(Component, (0, _extends3["default"])({}, this.props, withRef));
            }
        }));
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Form.Item"></a>[module antd.Form.Item](#apidoc.module.antd.Form.Item)

#### <a name="apidoc.element.antd.Form.Item.Item"></a>[function <span class="apidocSignatureSpan">antd.Form.</span>Item ()](#apidoc.element.antd.Form.Item.Item)
- description and source-code
```javascript
function FormItem() {
    (0, _classCallCheck3["default"])(this, FormItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Form.Item.prototype"></a>[module antd.Form.Item.prototype](#apidoc.module.antd.Form.Item.prototype)

#### <a name="apidoc.element.antd.Form.Item.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>componentDidMount ()](#apidoc.element.antd.Form.Item.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    (0, _warning2["default"])(this.getControls(this.props.children, true).length <= 1, ''Form.Item' cannot generate 'validateStatus
' and 'help' automatically, ' + 'while there are more than one 'getFieldDecorator' in it.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getChildProp"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getChildProp (prop)](#apidoc.element.antd.Form.Item.prototype.getChildProp)
- description and source-code
```javascript
function getChildProp(prop) {
    var child = this.getOnlyControl();
    return child && child.props && child.props[prop];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getControls"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getControls (children, recursively)](#apidoc.element.antd.Form.Item.prototype.getControls)
- description and source-code
```javascript
function getControls(children, recursively) {
    var controls = [];
    var childrenArray = _react2["default"].Children.toArray(children);
    for (var i = 0; i < childrenArray.length; i++) {
        if (!recursively && controls.length > 0) {
            break;
        }
        var child = childrenArray[i];
        if (child.type === FormItem) {
            continue;
        }
        if (!child.props) {
            continue;
        }
        if (_constants.FIELD_META_PROP in child.props) {
            controls.push(child);
        } else if (child.props.children) {
            controls = controls.concat(this.getControls(child.props.children, recursively));
        }
    }
    return controls;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getHelpMsg"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getHelpMsg ()](#apidoc.element.antd.Form.Item.prototype.getHelpMsg)
- description and source-code
```javascript
function getHelpMsg() {
    var context = this.context;
    var props = this.props;
    if (props.help === undefined && context.form) {
        return this.getId() ? (context.form.getFieldError(this.getId()) || []).join(', ') : '';
    }
    return props.help;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getId"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getId ()](#apidoc.element.antd.Form.Item.prototype.getId)
- description and source-code
```javascript
function getId() {
    return this.getChildProp('id');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getMeta"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getMeta ()](#apidoc.element.antd.Form.Item.prototype.getMeta)
- description and source-code
```javascript
function getMeta() {
    return this.getChildProp(_constants.FIELD_META_PROP);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getOnlyControl"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getOnlyControl ()](#apidoc.element.antd.Form.Item.prototype.getOnlyControl)
- description and source-code
```javascript
function getOnlyControl() {
    var child = this.getControls(this.props.children, false)[0];
    return child !== undefined ? child : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.getValidateStatus"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>getValidateStatus ()](#apidoc.element.antd.Form.Item.prototype.getValidateStatus)
- description and source-code
```javascript
function getValidateStatus() {
    var _context$form = this.context.form,
        isFieldValidating = _context$form.isFieldValidating,
        getFieldError = _context$form.getFieldError,
        getFieldValue = _context$form.getFieldValue;

    var fieldId = this.getId();
    if (!fieldId) {
        return '';
    }
    if (isFieldValidating(fieldId)) {
        return 'validating';
    }
    if (!!getFieldError(fieldId)) {
        return 'error';
    }
    var fieldValue = getFieldValue(fieldId);
    if (fieldValue !== undefined && fieldValue !== null && fieldValue !== '') {
        return 'success';
    }
    return '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.isRequired"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>isRequired ()](#apidoc.element.antd.Form.Item.prototype.isRequired)
- description and source-code
```javascript
function isRequired() {
    var required = this.props.required;

    if (required !== undefined) {
        return required;
    }
    if (this.context.form) {
        var meta = this.getMeta() || {};
        var validate = meta.validate || [];
        return validate.filter(function (item) {
            return !!item.rules;
        }).some(function (item) {
            return item.rules.some(function (rule) {
                return rule.required;
            });
        });
    }
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>render ()](#apidoc.element.antd.Form.Item.prototype.render)
- description and source-code
```javascript
function render() {
    var children = this.renderChildren();
    return this.renderFormItem(children);
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderChildren"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderChildren ()](#apidoc.element.antd.Form.Item.prototype.renderChildren)
- description and source-code
```javascript
function renderChildren() {
    var props = this.props;
    var children = _react2["default"].Children.map(props.children, function (child) {
        if (child && typeof child.type === 'function' && !child.props.size) {
            return _react2["default"].cloneElement(child, { size: 'large' });
        }
        return child;
    });
    return [this.renderLabel(), this.renderWrapper(this.renderValidateWrapper(children, this.renderHelp(), this.renderExtra()))];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderExtra"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderExtra ()](#apidoc.element.antd.Form.Item.prototype.renderExtra)
- description and source-code
```javascript
function renderExtra() {
    var _props = this.props,
        prefixCls = _props.prefixCls,
        extra = _props.extra;

    return extra ? _react2["default"].createElement(
        'div',
        { className: prefixCls + '-extra' },
        extra
    ) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderFormItem"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderFormItem (children)](#apidoc.element.antd.Form.Item.prototype.renderFormItem)
- description and source-code
```javascript
function renderFormItem(children) {
    var _itemClassName;

    var props = this.props;
    var prefixCls = props.prefixCls;
    var style = props.style;
    var itemClassName = (_itemClassName = {}, (0, _defineProperty3["default"])(_itemClassName, prefixCls + '-item', true), (0, _defineProperty3
["default"])(_itemClassName, prefixCls + '-item-with-help', !!this.getHelpMsg()), (0, _defineProperty3["default"])(_itemClassName
, prefixCls + '-item-no-colon', !props.colon), (0, _defineProperty3["default"])(_itemClassName, '' + props.className, !!props.className
), _itemClassName);
    return _react2["default"].createElement(
        _row2["default"],
        { className: (0, _classnames2["default"])(itemClassName), style: style },
        children
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderHelp"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderHelp ()](#apidoc.element.antd.Form.Item.prototype.renderHelp)
- description and source-code
```javascript
function renderHelp() {
    var prefixCls = this.props.prefixCls;
    var help = this.getHelpMsg();
    return help ? _react2["default"].createElement(
        'div',
        { className: prefixCls + '-explain', key: 'help' },
        help
    ) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderLabel"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderLabel ()](#apidoc.element.antd.Form.Item.prototype.renderLabel)
- description and source-code
```javascript
function renderLabel() {
    var _props2 = this.props,
        label = _props2.label,
        labelCol = _props2.labelCol,
        prefixCls = _props2.prefixCls,
        colon = _props2.colon,
        id = _props2.id;

    var context = this.context;
    var required = this.isRequired();
    var className = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-item-required', required));
    var labelChildren = label;
    // Keep label is original where there should have no colon
    var haveColon = colon && !context.vertical;
    // Remove duplicated user input colon
    if (haveColon && typeof label === 'string' && label.trim() !== '') {
        labelChildren = label.replace(/[：|:]\s*$/, '');
    }
    return label ? _react2["default"].createElement(
        _col2["default"],
        (0, _extends3["default"])({}, labelCol, { key: 'label', className: prefixCls + '-item-label' }),
        _react2["default"].createElement(
            'label',
            { htmlFor: id || this.getId(), className: className, title: typeof label === 'string' ? label : '' },
            labelChildren
        )
    ) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderValidateWrapper"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderValidateWrapper (c1, c2, c3)](#apidoc.element.antd.Form.Item.prototype.renderValidateWrapper)
- description and source-code
```javascript
function renderValidateWrapper(c1, c2, c3) {
    var classes = '';
    var form = this.context.form;
    var props = this.props;
    var validateStatus = props.validateStatus === undefined && form ? this.getValidateStatus() : props.validateStatus;
    if (validateStatus) {
        classes = (0, _classnames2["default"])({
            'has-feedback': props.hasFeedback,
            'has-success': validateStatus === 'success',
            'has-warning': validateStatus === 'warning',
            'has-error': validateStatus === 'error',
            'is-validating': validateStatus === 'validating'
        });
    }
    return _react2["default"].createElement(
        'div',
        { className: this.props.prefixCls + '-item-control ' + classes },
        c1,
        c2,
        c3
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.renderWrapper"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>renderWrapper (children)](#apidoc.element.antd.Form.Item.prototype.renderWrapper)
- description and source-code
```javascript
function renderWrapper(children) {
    var wrapperCol = this.props.wrapperCol;
    return _react2["default"].createElement(
        _col2["default"],
        (0, _extends3["default"])({ className: this.props.prefixCls + '-item-control-wrapper' }, wrapperCol, { key: 'wrapper' }),
        children
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.Item.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">antd.Form.Item.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Form.Item.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
    for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
    }

    return _PureRenderMixin2["default"].shouldComponentUpdate.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Form.childContextTypes"></a>[module antd.Form.childContextTypes](#apidoc.module.antd.Form.childContextTypes)

#### <a name="apidoc.element.antd.Form.childContextTypes.vertical"></a>[function <span class="apidocSignatureSpan">antd.Form.childContextTypes.</span>vertical ()](#apidoc.element.antd.Form.childContextTypes.vertical)
- description and source-code
```javascript
vertical = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Form.defaultProps"></a>[module antd.Form.defaultProps](#apidoc.module.antd.Form.defaultProps)

#### <a name="apidoc.element.antd.Form.defaultProps.onSubmit"></a>[function <span class="apidocSignatureSpan">antd.Form.defaultProps.</span>onSubmit (e)](#apidoc.element.antd.Form.defaultProps.onSubmit)
- description and source-code
```javascript
function onSubmit(e) {
    e.preventDefault();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Form.propTypes"></a>[module antd.Form.propTypes](#apidoc.module.antd.Form.propTypes)

#### <a name="apidoc.element.antd.Form.propTypes.children"></a>[function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>children ()](#apidoc.element.antd.Form.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.propTypes.hideRequiredMark"></a>[function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>hideRequiredMark ()](#apidoc.element.antd.Form.propTypes.hideRequiredMark)
- description and source-code
```javascript
hideRequiredMark = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.propTypes.layout"></a>[function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>layout ()](#apidoc.element.antd.Form.propTypes.layout)
- description and source-code
```javascript
layout = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.propTypes.onSubmit"></a>[function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>onSubmit ()](#apidoc.element.antd.Form.propTypes.onSubmit)
- description and source-code
```javascript
onSubmit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Form.propTypes.</span>prefixCls ()](#apidoc.element.antd.Form.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Form.prototype"></a>[module antd.Form.prototype](#apidoc.module.antd.Form.prototype)

#### <a name="apidoc.element.antd.Form.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">antd.Form.prototype.</span>getChildContext ()](#apidoc.element.antd.Form.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
    var _props = this.props,
        layout = _props.layout,
        vertical = _props.vertical;

    return {
        vertical: layout === 'vertical' || vertical
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Form.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Form.prototype.</span>render ()](#apidoc.element.antd.Form.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _props2 = this.props,
        prefixCls = _props2.prefixCls,
        hideRequiredMark = _props2.hideRequiredMark,
        _props2$className = _props2.className,
        className = _props2$className === undefined ? '' : _props2$className,
        layout = _props2.layout,
        inline = _props2.inline,
        horizontal = _props2.horizontal,
        vertical = _props2.vertical;

    (0, _warning2["default"])(!inline && !horizontal && !vertical, ''Form[inline|horizontal|vertical]' is deprecated, please use
 'Form[layout]' instead.');
    var formClassName = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames,
prefixCls + '-horizontal', !inline && !vertical && layout === 'horizontal' || horizontal), (0, _defineProperty3["default"])(_classNames
, prefixCls + '-vertical', layout === 'vertical' || vertical), (0, _defineProperty3["default"])(_classNames, prefixCls + '-inline
', layout === 'inline' || inline), (0, _defineProperty3["default"])(_classNames, prefixCls + '-hide-required-mark', hideRequiredMark
), _classNames), className);
    var formProps = (0, _omit2["default"])(this.props, ['prefixCls', 'className', 'layout', 'inline', 'horizontal', 'vertical', '
form', 'hideRequiredMark']);
    return _react2["default"].createElement('form', (0, _extends3["default"])({}, formProps, { className: formClassName }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Form.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">antd.Form.prototype.</span>shouldComponentUpdate ()](#apidoc.element.antd.Form.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate() {
    for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
        args[_key] = arguments[_key];
    }

    return _PureRenderMixin2["default"].shouldComponentUpdate.apply(this, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Input"></a>[module antd.Input](#apidoc.module.antd.Input)

#### <a name="apidoc.element.antd.Input.Input"></a>[function <span class="apidocSignatureSpan">antd.</span>Input ()](#apidoc.element.antd.Input.Input)
- description and source-code
```javascript
function Input() {
    (0, _classCallCheck3["default"])(this, Input);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));

    _this.state = {
        textareaStyles: null,
        isFocus: false
    };
    _this.handleKeyDown = function (e) {
        var _this$props = _this.props,
            onPressEnter = _this$props.onPressEnter,
            onKeyDown = _this$props.onKeyDown;

        if (e.keyCode === 13 && onPressEnter) {
            onPressEnter(e);
        }
        if (onKeyDown) {
            onKeyDown(e);
        }
    };
    _this.handleTextareaChange = function (e) {
        if (!('value' in _this.props)) {
            _this.resizeTextarea();
        }
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(e);
        }
    };
    _this.resizeTextarea = function () {
        var _this$props2 = _this.props,
            type = _this$props2.type,
            autosize = _this$props2.autosize;

        if (type !== 'textarea' || !autosize || !_this.refs.input) {
            return;
        }
        var minRows = autosize ? autosize.minRows : null;
        var maxRows = autosize ? autosize.maxRows : null;
        var textareaStyles = (0, _calculateNodeHeight2["default"])(_this.refs.input, false, minRows, maxRows);
        _this.setState({ textareaStyles: textareaStyles });
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.Group"></a>[function <span class="apidocSignatureSpan">antd.Input.</span>Group (props)](#apidoc.element.antd.Input.Group)
- description and source-code
```javascript
function Group(props) {
    var _classNames;

    var _props$prefixCls = props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? 'ant-input-group' : _props$prefixCls,
        _props$className = props.className,
        className = _props$className === undefined ? '' : _props$className;

    var cls = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-lg', props.size === 'large'), (0, _defineProperty3["default"])(_classNames, prefixCls + '-sm', props.size === 'small'), (0,
_defineProperty3["default"])(_classNames, prefixCls + '-compact', props.compact), _classNames), className);
    return _react2["default"].createElement(
        'span',
        { className: cls, style: props.style },
        props.children
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.Search"></a>[function <span class="apidocSignatureSpan">antd.Input.</span>Search ()](#apidoc.element.antd.Input.Search)
- description and source-code
```javascript
function Search() {
    (0, _classCallCheck3["default"])(this, Search);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.onSearch = function () {
        var onSearch = _this.props.onSearch;

        if (onSearch) {
            onSearch(_this.input.refs.input.value);
        }
        _this.input.refs.input.focus();
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Input.Search"></a>[module antd.Input.Search](#apidoc.module.antd.Input.Search)

#### <a name="apidoc.element.antd.Input.Search.Search"></a>[function <span class="apidocSignatureSpan">antd.Input.</span>Search ()](#apidoc.element.antd.Input.Search.Search)
- description and source-code
```javascript
function Search() {
    (0, _classCallCheck3["default"])(this, Search);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.onSearch = function () {
        var onSearch = _this.props.onSearch;

        if (onSearch) {
            onSearch(_this.input.refs.input.value);
        }
        _this.input.refs.input.focus();
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Input.Search.prototype"></a>[module antd.Input.Search.prototype](#apidoc.module.antd.Input.Search.prototype)

#### <a name="apidoc.element.antd.Input.Search.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Input.Search.prototype.</span>render ()](#apidoc.element.antd.Input.Search.prototype.render)
- description and source-code
```javascript
function render() {
    var _this2 = this;

    var _a = this.props,
        className = _a.className,
        prefixCls = _a.prefixCls,
        others = __rest(_a, ["className", "prefixCls"]);
    delete others.onSearch;
    var searchSuffix = _react2["default"].createElement(_icon2["default"], { className: prefixCls + '-icon', onClick: this.onSearch
, type: 'search' });
    return _react2["default"].createElement(_Input2["default"], (0, _extends3["default"])({ className: (0, _classnames2["default
"])(prefixCls, className), onPressEnter: this.onSearch, ref: function ref(node) {
            return _this2.input = node;
        }, suffix: searchSuffix }, others));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Input.propTypes"></a>[module antd.Input.propTypes](#apidoc.module.antd.Input.propTypes)

#### <a name="apidoc.element.antd.Input.propTypes.addonAfter"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>addonAfter ()](#apidoc.element.antd.Input.propTypes.addonAfter)
- description and source-code
```javascript
addonAfter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.addonBefore"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>addonBefore ()](#apidoc.element.antd.Input.propTypes.addonBefore)
- description and source-code
```javascript
addonBefore = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.autosize"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>autosize ()](#apidoc.element.antd.Input.propTypes.autosize)
- description and source-code
```javascript
autosize = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>className ()](#apidoc.element.antd.Input.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.defaultValue"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>defaultValue ()](#apidoc.element.antd.Input.propTypes.defaultValue)
- description and source-code
```javascript
defaultValue = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.disabled"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>disabled ()](#apidoc.element.antd.Input.propTypes.disabled)
- description and source-code
```javascript
disabled = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.id"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>id ()](#apidoc.element.antd.Input.propTypes.id)
- description and source-code
```javascript
id = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.onBlur"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onBlur ()](#apidoc.element.antd.Input.propTypes.onBlur)
- description and source-code
```javascript
onBlur = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.onFocus"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onFocus ()](#apidoc.element.antd.Input.propTypes.onFocus)
- description and source-code
```javascript
onFocus = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.onKeyDown"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onKeyDown ()](#apidoc.element.antd.Input.propTypes.onKeyDown)
- description and source-code
```javascript
onKeyDown = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.onPressEnter"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>onPressEnter ()](#apidoc.element.antd.Input.propTypes.onPressEnter)
- description and source-code
```javascript
onPressEnter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.prefix"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>prefix ()](#apidoc.element.antd.Input.propTypes.prefix)
- description and source-code
```javascript
prefix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>prefixCls ()](#apidoc.element.antd.Input.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.size"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>size ()](#apidoc.element.antd.Input.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.suffix"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>suffix ()](#apidoc.element.antd.Input.propTypes.suffix)
- description and source-code
```javascript
suffix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.type"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>type ()](#apidoc.element.antd.Input.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.propTypes.value"></a>[function <span class="apidocSignatureSpan">antd.Input.propTypes.</span>value ()](#apidoc.element.antd.Input.propTypes.value)
- description and source-code
```javascript
value = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Input.prototype"></a>[module antd.Input.prototype](#apidoc.module.antd.Input.prototype)

#### <a name="apidoc.element.antd.Input.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>componentDidMount ()](#apidoc.element.antd.Input.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    this.resizeTextarea();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Input.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    // Re-render with the new content then recalculate the height as required.
    if (this.props.value !== nextProps.value) {
        if (this.nextFrameActionId) {
            clearNextFrameAction(this.nextFrameActionId);
        }
        this.nextFrameActionId = onNextFrame(this.resizeTextarea);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.prototype.focus"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>focus ()](#apidoc.element.antd.Input.prototype.focus)
- description and source-code
```javascript
function focus() {
    this.refs.input.focus();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>render ()](#apidoc.element.antd.Input.prototype.render)
- description and source-code
```javascript
function render() {
    return this.renderLabeledInput(this.renderInput());
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Input.prototype.renderInput"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>renderInput ()](#apidoc.element.antd.Input.prototype.renderInput)
- description and source-code
```javascript
function renderInput() {
    var _classNames2;

    var props = (0, _objectAssign2["default"])({}, this.props);
    // Fix https://fb.me/react-unknown-prop
    var otherProps = (0, _omit2["default"])(this.props, ['prefixCls', 'onPressEnter', 'autosize', 'addonBefore', 'addonAfter', '
prefix', 'suffix']);
    var prefixCls = props.prefixCls;
    if (!props.type) {
        return props.children;
    }
    var inputClassName = (0, _classnames2["default"])(prefixCls, (_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2
, prefixCls + '-sm', props.size === 'small'), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-lg', props.size === '
large'), _classNames2), props.className);
    if ('value' in props) {
        otherProps.value = fixControlledValue(props.value);
        // Input elements must be either controlled or uncontrolled,
        // specify either the value prop, or the defaultValue prop, but not both.
        delete otherProps.defaultValue;
    }
    switch (props.type) {
        case 'textarea':
            return _react2["default"].createElement('textarea', (0, _extends3["default"])({}, otherProps, { style: (0, _objectAssign2
["default"])({}, props.style, this.state.textareaStyles), className: inputClassName, onKeyDown: this.handleKeyDown, onChange: this
.handleTextareaChange, ref: 'input' }));
        default:
            return this.renderLabeledIcon(_react2["default"].createElement('input', (0, _extends3["default"])({}, otherProps, {
className: inputClassName, onKeyDown: this.handleKeyDown, ref: 'input' })));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.prototype.renderLabeledIcon"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>renderLabeledIcon (children)](#apidoc.element.antd.Input.prototype.renderLabeledIcon)
- description and source-code
```javascript
function renderLabeledIcon(children) {
    var props = this.props;

    if (props.type === 'textarea' || !('prefix' in props || 'suffix' in props)) {
        return children;
    }
    var prefix = props.prefix ? _react2["default"].createElement(
        'span',
        { className: props.prefixCls + '-prefix' },
        props.prefix
    ) : null;
    var suffix = props.suffix ? _react2["default"].createElement(
        'span',
        { className: props.prefixCls + '-suffix' },
        props.suffix
    ) : null;
    return _react2["default"].createElement(
        'span',
        { className: props.prefixCls + '-affix-wrapper', style: props.style },
        prefix,
        (0, _react.cloneElement)(children, { style: null }),
        suffix
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Input.prototype.renderLabeledInput"></a>[function <span class="apidocSignatureSpan">antd.Input.prototype.</span>renderLabeledInput (children)](#apidoc.element.antd.Input.prototype.renderLabeledInput)
- description and source-code
```javascript
function renderLabeledInput(children) {
    var _classNames;

    var props = this.props;
    // Not wrap when there is not addons
    if (props.type === 'textarea' || !props.addonBefore && !props.addonAfter) {
        return children;
    }
    var wrapperClassName = props.prefixCls + '-group';
    var addonClassName = wrapperClassName + '-addon';
    var addonBefore = props.addonBefore ? _react2["default"].createElement(
        'span',
        { className: addonClassName },
        props.addonBefore
    ) : null;
    var addonAfter = props.addonAfter ? _react2["default"].createElement(
        'span',
        { className: addonClassName },
        props.addonAfter
    ) : null;
    var className = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, props.prefixCls
 + '-wrapper', true), (0, _defineProperty3["default"])(_classNames, wrapperClassName, addonBefore || addonAfter), _classNames));
    return _react2["default"].createElement(
        'span',
        { className: className },
        addonBefore,
        children,
        addonAfter
    );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.InputNumber"></a>[module antd.InputNumber](#apidoc.module.antd.InputNumber)

#### <a name="apidoc.element.antd.InputNumber.InputNumber"></a>[function <span class="apidocSignatureSpan">antd.</span>InputNumber ()](#apidoc.element.antd.InputNumber.InputNumber)
- description and source-code
```javascript
function InputNumber() {
    (0, _classCallCheck3["default"])(this, InputNumber);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.InputNumber.prototype"></a>[module antd.InputNumber.prototype](#apidoc.module.antd.InputNumber.prototype)

#### <a name="apidoc.element.antd.InputNumber.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.InputNumber.prototype.</span>render ()](#apidoc.element.antd.InputNumber.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        className = _a.className,
        size = _a.size,
        others = __rest(_a, ["className", "size"]);
    var inputNumberClass = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, this.props
.prefixCls + '-lg', size === 'large'), (0, _defineProperty3["default"])(_classNames, this.props.prefixCls + '-sm', size === 'small
'), _classNames), className);
    return _react2["default"].createElement(_rcInputNumber2["default"], (0, _extends3["default"])({ className: inputNumberClass },
others));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Layout"></a>[module antd.Layout](#apidoc.module.antd.Layout)

#### <a name="apidoc.element.antd.Layout.Layout"></a>[function <span class="apidocSignatureSpan">antd.</span>Layout ()](#apidoc.element.antd.Layout.Layout)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Content"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Content ()](#apidoc.element.antd.Layout.Content)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Footer"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Footer ()](#apidoc.element.antd.Layout.Footer)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Header"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Header ()](#apidoc.element.antd.Layout.Header)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Sider"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Sider (props)](#apidoc.element.antd.Layout.Sider)
- description and source-code
```javascript
function Sider(props) {
    (0, _classCallCheck3["default"])(this, Sider);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.responsiveHandler = function (mql) {
        _this.setState({ below: mql.matches });
        if (_this.state.collapsed !== mql.matches) {
            _this.setCollapsed(mql.matches, 'responsive');
        }
    };
    _this.setCollapsed = function (collapsed, type) {
        if (!('collapsed' in _this.props)) {
            _this.setState({
                collapsed: collapsed
            });
        }
        var onCollapse = _this.props.onCollapse;

        if (onCollapse) {
            onCollapse(collapsed, type);
        }
    };
    _this.toggle = function () {
        var collapsed = !_this.state.collapsed;
        _this.setCollapsed(collapsed, 'clickTrigger');
    };
    _this.belowShowChange = function () {
        _this.setState({ belowShow: !_this.state.belowShow });
    };
    var matchMedia = void 0;
    if (typeof window !== 'undefined') {
        matchMedia = window.matchMedia;
    }
    if (matchMedia && props.breakpoint && props.breakpoint in dimensionMap) {
        _this.mql = matchMedia('(max-width: ' + dimensionMap[props.breakpoint] + ')');
    }
    var collapsed = void 0;
    if ('collapsed' in props) {
        collapsed = props.collapsed;
    } else {
        collapsed = props.defaultCollapsed;
    }
    _this.state = {
        collapsed: collapsed,
        below: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Layout.Content"></a>[module antd.Layout.Content](#apidoc.module.antd.Layout.Content)

#### <a name="apidoc.element.antd.Layout.Content.Content"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Content ()](#apidoc.element.antd.Layout.Content.Content)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Layout.Content.prototype"></a>[module antd.Layout.Content.prototype](#apidoc.module.antd.Layout.Content.prototype)

#### <a name="apidoc.element.antd.Layout.Content.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Layout.Content.prototype.</span>render ()](#apidoc.element.antd.Layout.Content.prototype.render)
- description and source-code
```javascript
function render() {
    var prefixCls = props.prefixCls;

    return _react2["default"].createElement(Basic, (0, _extends3["default"])({ prefixCls: prefixCls }, this.props));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Layout.Footer"></a>[module antd.Layout.Footer](#apidoc.module.antd.Layout.Footer)

#### <a name="apidoc.element.antd.Layout.Footer.Footer"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Footer ()](#apidoc.element.antd.Layout.Footer.Footer)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Layout.Footer.prototype"></a>[module antd.Layout.Footer.prototype](#apidoc.module.antd.Layout.Footer.prototype)

#### <a name="apidoc.element.antd.Layout.Footer.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Layout.Footer.prototype.</span>render ()](#apidoc.element.antd.Layout.Footer.prototype.render)
- description and source-code
```javascript
function render() {
    var prefixCls = props.prefixCls;

    return _react2["default"].createElement(Basic, (0, _extends3["default"])({ prefixCls: prefixCls }, this.props));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Layout.Header"></a>[module antd.Layout.Header](#apidoc.module.antd.Layout.Header)

#### <a name="apidoc.element.antd.Layout.Header.Header"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Header ()](#apidoc.element.antd.Layout.Header.Header)
- description and source-code
```javascript
function Adapter() {
    (0, _classCallCheck3["default"])(this, Adapter);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Layout.Header.prototype"></a>[module antd.Layout.Header.prototype](#apidoc.module.antd.Layout.Header.prototype)

#### <a name="apidoc.element.antd.Layout.Header.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Layout.Header.prototype.</span>render ()](#apidoc.element.antd.Layout.Header.prototype.render)
- description and source-code
```javascript
function render() {
    var prefixCls = props.prefixCls;

    return _react2["default"].createElement(Basic, (0, _extends3["default"])({ prefixCls: prefixCls }, this.props));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Layout.Sider"></a>[module antd.Layout.Sider](#apidoc.module.antd.Layout.Sider)

#### <a name="apidoc.element.antd.Layout.Sider.Sider"></a>[function <span class="apidocSignatureSpan">antd.Layout.</span>Sider (props)](#apidoc.element.antd.Layout.Sider.Sider)
- description and source-code
```javascript
function Sider(props) {
    (0, _classCallCheck3["default"])(this, Sider);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.responsiveHandler = function (mql) {
        _this.setState({ below: mql.matches });
        if (_this.state.collapsed !== mql.matches) {
            _this.setCollapsed(mql.matches, 'responsive');
        }
    };
    _this.setCollapsed = function (collapsed, type) {
        if (!('collapsed' in _this.props)) {
            _this.setState({
                collapsed: collapsed
            });
        }
        var onCollapse = _this.props.onCollapse;

        if (onCollapse) {
            onCollapse(collapsed, type);
        }
    };
    _this.toggle = function () {
        var collapsed = !_this.state.collapsed;
        _this.setCollapsed(collapsed, 'clickTrigger');
    };
    _this.belowShowChange = function () {
        _this.setState({ belowShow: !_this.state.belowShow });
    };
    var matchMedia = void 0;
    if (typeof window !== 'undefined') {
        matchMedia = window.matchMedia;
    }
    if (matchMedia && props.breakpoint && props.breakpoint in dimensionMap) {
        _this.mql = matchMedia('(max-width: ' + dimensionMap[props.breakpoint] + ')');
    }
    var collapsed = void 0;
    if ('collapsed' in props) {
        collapsed = props.collapsed;
    } else {
        collapsed = props.defaultCollapsed;
    }
    _this.state = {
        collapsed: collapsed,
        below: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Layout.Sider.prototype"></a>[module antd.Layout.Sider.prototype](#apidoc.module.antd.Layout.Sider.prototype)

#### <a name="apidoc.element.antd.Layout.Sider.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>componentDidMount ()](#apidoc.element.antd.Layout.Sider.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    if (this.mql) {
        this.mql.addListener(this.responsiveHandler);
        this.responsiveHandler(this.mql);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Sider.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Layout.Sider.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('collapsed' in nextProps) {
        this.setState({
            collapsed: nextProps.collapsed
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Sider.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Layout.Sider.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    if (this.mql) {
        this.mql.removeListener(this.responsiveHandler);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Layout.Sider.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Layout.Sider.prototype.</span>render ()](#apidoc.element.antd.Layout.Sider.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        prefixCls = _a.prefixCls,
        className = _a.className,
        collapsible = _a.collapsible,
        reverseArrow = _a.reverseArrow,
        trigger = _a.trigger,
        style = _a.style,
        width = _a.width,
        collapsedWidth = _a.collapsedWidth,
        others = __rest(_a, ["prefixCls", "className", "collapsible", "reverseArrow", "trigger", "style", "width", "collapsedWidth
"]);
    var divProps = (0, _omit2["default"])(others, ['collapsed', 'defaultCollapsed', 'onCollapse', 'breakpoint']);
    var siderWidth = this.state.collapsed ? collapsedWidth : width;
    // special trigger when collapsedWidth == 0
    var zeroWidthTrigger = collapsedWidth === 0 || collapsedWidth === '0' ? _react2["default"].createElement(
        'span',
        { onClick: this.toggle, className: prefixCls + '-zero-width-trigger' },
        _react2["default"].createElement(_icon2["default"], { type: 'bars' })
    ) : null;
    var iconObj = {
        'expanded': reverseArrow ? _react2["default"].createElement(_icon2["default"], { type: 'right' }) : _react2["default"].createElement
(_icon2["default"], { type: 'left' }),
        'collapsed': reverseArrow ? _react2["default"].createElement(_icon2["default"], { type: 'left' }) : _react2["default"].createElement
(_icon2["default"], { type: 'right' })
    };
    var status = this.state.collapsed ? 'collapsed' : 'expanded';
    var defaultTrigger = iconObj[status];
    var triggerDom = trigger !== null ? zeroWidthTrigger || _react2["default"].createElement(
        'div',
        { className: prefixCls + '-trigger', onClick: this.toggle },
        trigger || defaultTrigger
    ) : null;
    var divStyle = (0, _extends3["default"])({}, style, { flex: '0 0 ' + siderWidth + 'px', width: siderWidth + 'px' });
    var siderCls = (0, _classnames2["default"])(className, prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames
, prefixCls + '-collapsed', !!this.state.collapsed), (0, _defineProperty3["default"])(_classNames, prefixCls + '-has-trigger', !!
trigger), (0, _defineProperty3["default"])(_classNames, prefixCls + '-below', !!this.state.below), (0, _defineProperty3["default
"])(_classNames, prefixCls + '-zero-width', siderWidth === 0 || siderWidth === '0'), _classNames));
    return _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({ className: siderCls }, divProps, { style: divStyle }),
        this.props.children,
        collapsible || this.state.below && zeroWidthTrigger ? triggerDom : null
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Layout.prototype"></a>[module antd.Layout.prototype](#apidoc.module.antd.Layout.prototype)

#### <a name="apidoc.element.antd.Layout.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Layout.prototype.</span>render ()](#apidoc.element.antd.Layout.prototype.render)
- description and source-code
```javascript
function render() {
    var prefixCls = props.prefixCls;

    return _react2["default"].createElement(Basic, (0, _extends3["default"])({ prefixCls: prefixCls }, this.props));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.LocaleProvider"></a>[module antd.LocaleProvider](#apidoc.module.antd.LocaleProvider)

#### <a name="apidoc.element.antd.LocaleProvider.LocaleProvider"></a>[function <span class="apidocSignatureSpan">antd.</span>LocaleProvider ()](#apidoc.element.antd.LocaleProvider.LocaleProvider)
- description and source-code
```javascript
function LocaleProvider() {
    (0, _classCallCheck3["default"])(this, LocaleProvider);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.LocaleProvider.childContextTypes"></a>[module antd.LocaleProvider.childContextTypes](#apidoc.module.antd.LocaleProvider.childContextTypes)

#### <a name="apidoc.element.antd.LocaleProvider.childContextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.childContextTypes.</span>antLocale ()](#apidoc.element.antd.LocaleProvider.childContextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.LocaleProvider.propTypes"></a>[module antd.LocaleProvider.propTypes](#apidoc.module.antd.LocaleProvider.propTypes)

#### <a name="apidoc.element.antd.LocaleProvider.propTypes.locale"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.propTypes.</span>locale ()](#apidoc.element.antd.LocaleProvider.propTypes.locale)
- description and source-code
```javascript
locale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.LocaleProvider.prototype"></a>[module antd.LocaleProvider.prototype](#apidoc.module.antd.LocaleProvider.prototype)

#### <a name="apidoc.element.antd.LocaleProvider.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.LocaleProvider.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
    var locale = this.props.locale;

    (0, _locale.changeConfirmLocale)(locale && locale.Modal);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.LocaleProvider.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>componentWillMount ()](#apidoc.element.antd.LocaleProvider.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
    this.componentDidUpdate();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.LocaleProvider.prototype.componentWillUnMount"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>componentWillUnMount ()](#apidoc.element.antd.LocaleProvider.prototype.componentWillUnMount)
- description and source-code
```javascript
function componentWillUnMount() {
    (0, _locale.changeConfirmLocale)();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.LocaleProvider.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>getChildContext ()](#apidoc.element.antd.LocaleProvider.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
    return {
        antLocale: (0, _extends3["default"])({}, this.props.locale, { exist: true })
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.LocaleProvider.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.LocaleProvider.prototype.</span>render ()](#apidoc.element.antd.LocaleProvider.prototype.render)
- description and source-code
```javascript
function render() {
    return _react2["default"].Children.only(this.props.children);
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Mention"></a>[module antd.Mention](#apidoc.module.antd.Mention)

#### <a name="apidoc.element.antd.Mention.Mention"></a>[function <span class="apidocSignatureSpan">antd.</span>Mention {{signature}}](#apidoc.element.antd.Mention.Mention)
- description and source-code
```javascript
n/a
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.Nav"></a>[function <span class="apidocSignatureSpan">antd.Mention.</span>Nav ()](#apidoc.element.antd.Mention.Nav)
- description and source-code
```javascript
function Nav() {
  _classCallCheck(this, Nav);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.getMentions"></a>[function <span class="apidocSignatureSpan">antd.Mention.</span>getMentions (editorState)](#apidoc.element.antd.Mention.getMentions)
- description and source-code
```javascript
function getMentions(editorState) {
  var prefix = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : '@';

  var regex = (0, _getRegExp2["default"])(prefix);
  var contentState = editorState.getCurrentContent();
  var entities = [];
  contentState.getBlockMap().forEach(function (block) {
    var blockText = block.getText();
    var matchArr = void 0;
    while ((matchArr = regex.exec(blockText)) !== null) {
      // eslint-disable-line
      entities.push(matchArr[0].trim());
    }
  });
  return entities;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.toEditorState"></a>[function <span class="apidocSignatureSpan">antd.Mention.</span>toEditorState (text)](#apidoc.element.antd.Mention.toEditorState)
- description and source-code
```javascript
function ToEditorState(text) {
    var createEmptyContentState = _draftJs.ContentState.createFromText((0, _exportText.decodeContent)(text) || '');
    var editorState = _draftJs.EditorState.createWithContent(createEmptyContentState);
    return _draftJs.EditorState.forceSelection(editorState, createEmptyContentState.getSelectionAfter());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.toString"></a>[function <span class="apidocSignatureSpan">antd.Mention.</span>toString (editorState)](#apidoc.element.antd.Mention.toString)
- description and source-code
```javascript
function exportContent(editorState) {
  var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

  var content = editorState.getCurrentContent();
  return new MentionGenerator(content, options).generate();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Mention.Nav"></a>[module antd.Mention.Nav](#apidoc.module.antd.Mention.Nav)

#### <a name="apidoc.element.antd.Mention.Nav.Nav"></a>[function <span class="apidocSignatureSpan">antd.Mention.</span>Nav ()](#apidoc.element.antd.Mention.Nav.Nav)
- description and source-code
```javascript
function Nav() {
  _classCallCheck(this, Nav);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Mention.Nav.prototype"></a>[module antd.Mention.Nav.prototype](#apidoc.module.antd.Mention.Nav.prototype)

#### <a name="apidoc.element.antd.Mention.Nav.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Mention.Nav.prototype.</span>render ()](#apidoc.element.antd.Mention.Nav.prototype.render)
- description and source-code
```javascript
function render() {
  return _react2["default"].createElement(
    'div',
    this.props,
    this.props.children
  );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Mention.prototype"></a>[module antd.Mention.prototype](#apidoc.module.antd.Mention.prototype)

#### <a name="apidoc.element.antd.Mention.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Mention.prototype.</span>componentWillReceiveProps (_ref)](#apidoc.element.antd.Mention.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(_ref) {
    var suggestions = _ref.suggestions;

    if (!(0, _shallowequal2["default"])(suggestions, this.props.suggestions)) {
        this.setState({
            suggestions: suggestions
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.prototype.defaultSearchChange"></a>[function <span class="apidocSignatureSpan">antd.Mention.prototype.</span>defaultSearchChange (value)](#apidoc.element.antd.Mention.prototype.defaultSearchChange)
- description and source-code
```javascript
function defaultSearchChange(value) {
    var searchValue = value.toLowerCase();
    var filteredSuggestions = (this.props.suggestions || []).filter(function (suggestion) {
        return suggestion.toLowerCase().indexOf(searchValue) !== -1;
    });
    this.setState({
        suggestions: filteredSuggestions
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Mention.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Mention.prototype.</span>render ()](#apidoc.element.antd.Mention.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        prefixCls = _props.prefixCls,
        loading = _props.loading;
    var _state = this.state,
        suggestions = _state.suggestions,
        focus = _state.focus;

    var cls = (0, _classnames2["default"])(className, (0, _defineProperty3["default"])({}, prefixCls + '-active', focus));
    var notFoundContent = loading ? _react2["default"].createElement(_icon2["default"], { type: 'loading' }) : this.props.notFoundContent
;
    return _react2["default"].createElement(_rcEditorMention2["default"], (0, _extends3["default"])({}, this.props, { className:
cls, onSearchChange: this.onSearchChange, onChange: this.onChange, onFocus: this.onFocus, onBlur: this.onBlur, suggestions: suggestions
, notFoundContent: notFoundContent }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Menu"></a>[module antd.Menu](#apidoc.module.antd.Menu)

#### <a name="apidoc.element.antd.Menu.Menu"></a>[function <span class="apidocSignatureSpan">antd.</span>Menu (props)](#apidoc.element.antd.Menu.Menu)
- description and source-code
```javascript
function Menu(props) {
    (0, _classCallCheck3["default"])(this, Menu);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.handleClick = function (e) {
        _this.setOpenKeys([]);
        var onClick = _this.props.onClick;

        if (onClick) {
            onClick(e);
        }
    };
    _this.handleOpenChange = function (openKeys) {
        _this.setOpenKeys(openKeys);
        var onOpenChange = _this.props.onOpenChange;

        if (onOpenChange) {
            onOpenChange(openKeys);
        }
    };
    (0, _warning2["default"])(!('onOpen' in props || 'onClose' in props), ''onOpen' and 'onClose' are removed, please use 'onOpenChange
' instead, ' + 'see: http://u.ant.design/menu-on-open-change.');
    var openKeys = void 0;
    if ('defaultOpenKeys' in props) {
        openKeys = props.defaultOpenKeys;
    } else if ('openKeys' in props) {
        openKeys = props.openKeys;
    }
    _this.state = {
        openKeys: openKeys || []
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Divider"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>Divider (props, context, updater)](#apidoc.element.antd.Menu.Divider)
- description and source-code
```javascript
Divider = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>Item (props, context, updater)](#apidoc.element.antd.Menu.Item)
- description and source-code
```javascript
Item = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.ItemGroup"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>ItemGroup (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup)
- description and source-code
```javascript
ItemGroup = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>SubMenu (props, context, updater)](#apidoc.element.antd.Menu.SubMenu)
- description and source-code
```javascript
SubMenu = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.Divider"></a>[module antd.Menu.Divider](#apidoc.module.antd.Menu.Divider)

#### <a name="apidoc.element.antd.Menu.Divider.Divider"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>Divider (props, context, updater)](#apidoc.element.antd.Menu.Divider.Divider)
- description and source-code
```javascript
Divider = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Divider.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.Menu.Divider.</span>getDefaultProps ()](#apidoc.element.antd.Menu.Divider.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    disabled: true
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.Divider.prototype"></a>[module antd.Menu.Divider.prototype](#apidoc.module.antd.Menu.Divider.prototype)

#### <a name="apidoc.element.antd.Menu.Divider.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.Divider.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Divider.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.Divider.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Divider.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.</span>render ()](#apidoc.element.antd.Menu.Divider.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      _props$className = _props.className,
      className = _props$className === undefined ? '' : _props$className,
      rootPrefixCls = _props.rootPrefixCls;

  return _react2["default"].createElement('li', { className: className + ' ' + rootPrefixCls + '-item-divider' });
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Menu.Divider.prototype.__reactAutoBindMap"></a>[module antd.Menu.Divider.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.Divider.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.Menu.Divider.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.Divider.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.Divider.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.Item"></a>[module antd.Menu.Item](#apidoc.module.antd.Menu.Item)

#### <a name="apidoc.element.antd.Menu.Item.Item"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>Item (props, context, updater)](#apidoc.element.antd.Menu.Item.Item)
- description and source-code
```javascript
Item = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.</span>getDefaultProps ()](#apidoc.element.antd.Menu.Item.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    onSelect: _util.noop,
    onMouseEnter: _util.noop,
    onMouseLeave: _util.noop
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.Item.prototype"></a>[module antd.Menu.Item.prototype](#apidoc.module.antd.Menu.Item.prototype)

#### <a name="apidoc.element.antd.Menu.Item.prototype.clearMenuItemMouseLeaveTimer"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>clearMenuItemMouseLeaveTimer ()](#apidoc.element.antd.Menu.Item.prototype.clearMenuItemMouseLeaveTimer)
- description and source-code
```javascript
function clearMenuItemMouseLeaveTimer() {
  var props = this.props;
  var callFn = void 0;
  var parentMenu = props.parentMenu;
  if (parentMenu.menuItemMouseLeaveTimer) {
    clearTimeout(parentMenu.menuItemMouseLeaveTimer);
    parentMenu.menuItemMouseLeaveTimer = null;
    if (callFn && parentMenu.menuItemMouseLeaveFn) {
      parentMenu.menuItemMouseLeaveFn();
    }
    parentMenu.menuItemMouseLeaveFn = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Menu.Item.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  var props = this.props;
  if (props.onDestroy) {
    props.onDestroy(props.eventKey);
  }
  if (props.parentMenu.menuItemInstance === this) {
    this.clearMenuItemMouseLeaveTimer();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.Item.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.getActiveClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getActiveClassName ()](#apidoc.element.antd.Menu.Item.prototype.getActiveClassName)
- description and source-code
```javascript
function getActiveClassName() {
  return this.getPrefixCls() + '-active';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.Item.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.getDisabledClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.Item.prototype.getDisabledClassName)
- description and source-code
```javascript
function getDisabledClassName() {
  return this.getPrefixCls() + '-disabled';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.getPrefixCls"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getPrefixCls ()](#apidoc.element.antd.Menu.Item.prototype.getPrefixCls)
- description and source-code
```javascript
function getPrefixCls() {
  return this.props.rootPrefixCls + '-item';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.getSelectedClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.Item.prototype.getSelectedClassName)
- description and source-code
```javascript
function getSelectedClassName() {
  return this.getPrefixCls() + '-selected';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.isSelected"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>isSelected ()](#apidoc.element.antd.Menu.Item.prototype.isSelected)
- description and source-code
```javascript
function isSelected() {
  return this.props.selectedKeys.indexOf(this.props.eventKey) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.onClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onClick (e)](#apidoc.element.antd.Menu.Item.prototype.onClick)
- description and source-code
```javascript
function onClick(e) {
  var props = this.props;
  var selected = this.isSelected();
  var eventKey = props.eventKey;
  var info = {
    key: eventKey,
    keyPath: [eventKey],
    item: this,
    domEvent: e
  };
  props.onClick(info);
  if (props.multiple) {
    if (selected) {
      props.onDeselect(info);
    } else {
      props.onSelect(info);
    }
  } else if (!selected) {
    props.onSelect(info);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.onKeyDown"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onKeyDown (e)](#apidoc.element.antd.Menu.Item.prototype.onKeyDown)
- description and source-code
```javascript
function onKeyDown(e) {
  var keyCode = e.keyCode;
  if (keyCode === _KeyCode2["default"].ENTER) {
    this.onClick(e);
    return true;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.onMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.Item.prototype.onMouseEnter)
- description and source-code
```javascript
function onMouseEnter(e) {
  var props = this.props;
  var eventKey = props.eventKey,
      parentMenu = props.parentMenu;

  this.clearMenuItemMouseLeaveTimer(parentMenu.menuItemInstance !== this);
  if (parentMenu.subMenuInstance) {
    parentMenu.subMenuInstance.clearSubMenuTimers();
  }
  props.onItemHover({
    key: eventKey,
    item: this,
    hover: true,
    domEvent: e,
    trigger: 'mouseenter'
  });
  props.onMouseEnter({
    key: eventKey,
    domEvent: e
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.onMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.Item.prototype.onMouseLeave)
- description and source-code
```javascript
function onMouseLeave(e) {
  var _this = this;

  var props = this.props;
  var eventKey = props.eventKey,
      parentMenu = props.parentMenu;

  parentMenu.menuItemInstance = this;
  parentMenu.menuItemMouseLeaveFn = function () {
    if (_this.isMounted() && props.active) {
      props.onItemHover({
        key: eventKey,
        item: _this,
        hover: false,
        domEvent: e,
        trigger: 'mouseleave'
      });
    }
  };
  parentMenu.menuItemMouseLeaveTimer = setTimeout(parentMenu.menuItemMouseLeaveFn, 30);
  props.onMouseLeave({
    key: eventKey,
    domEvent: e
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.</span>render ()](#apidoc.element.antd.Menu.Item.prototype.render)
- description and source-code
```javascript
function render() {
  var props = this.props;
  var selected = this.isSelected();
  var classes = {};
  classes[this.getActiveClassName()] = !props.disabled && props.active;
  classes[this.getSelectedClassName()] = selected;
  classes[this.getDisabledClassName()] = props.disabled;
  classes[this.getPrefixCls()] = true;
  classes[props.className] = !!props.className;
  var attrs = (0, _extends3["default"])({}, props.attribute, {
    title: props.title,
    className: (0, _classnames2["default"])(classes),
    role: 'menuitem',
    'aria-selected': selected,
    'aria-disabled': props.disabled
  });
  var mouseEvent = {};
  if (!props.disabled) {
    mouseEvent = {
      onClick: this.onClick,
      onMouseLeave: this.onMouseLeave,
      onMouseEnter: this.onMouseEnter
    };
  }
  var style = (0, _extends3["default"])({}, props.style);
  if (props.mode === 'inline') {
    style.paddingLeft = props.inlineIndent * props.level;
  }
  return _react2["default"].createElement(
    'li',
    (0, _extends3["default"])({
      style: style
    }, attrs, mouseEvent),
    props.children
  );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Menu.Item.prototype.__reactAutoBindMap"></a>[module antd.Menu.Item.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.Item.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.clearMenuItemMouseLeaveTimer"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>clearMenuItemMouseLeaveTimer ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.clearMenuItemMouseLeaveTimer)
- description and source-code
```javascript
function clearMenuItemMouseLeaveTimer() {
  var props = this.props;
  var callFn = void 0;
  var parentMenu = props.parentMenu;
  if (parentMenu.menuItemMouseLeaveTimer) {
    clearTimeout(parentMenu.menuItemMouseLeaveTimer);
    parentMenu.menuItemMouseLeaveTimer = null;
    if (callFn && parentMenu.menuItemMouseLeaveFn) {
      parentMenu.menuItemMouseLeaveFn();
    }
    parentMenu.menuItemMouseLeaveFn = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getActiveClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getActiveClassName ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getActiveClassName)
- description and source-code
```javascript
function getActiveClassName() {
  return this.getPrefixCls() + '-active';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getDisabledClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getDisabledClassName)
- description and source-code
```javascript
function getDisabledClassName() {
  return this.getPrefixCls() + '-disabled';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getPrefixCls"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getPrefixCls ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getPrefixCls)
- description and source-code
```javascript
function getPrefixCls() {
  return this.props.rootPrefixCls + '-item';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getSelectedClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.getSelectedClassName)
- description and source-code
```javascript
function getSelectedClassName() {
  return this.getPrefixCls() + '-selected';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.isSelected"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>isSelected ()](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.isSelected)
- description and source-code
```javascript
function isSelected() {
  return this.props.selectedKeys.indexOf(this.props.eventKey) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onClick (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onClick)
- description and source-code
```javascript
function onClick(e) {
  var props = this.props;
  var selected = this.isSelected();
  var eventKey = props.eventKey;
  var info = {
    key: eventKey,
    keyPath: [eventKey],
    item: this,
    domEvent: e
  };
  props.onClick(info);
  if (props.multiple) {
    if (selected) {
      props.onDeselect(info);
    } else {
      props.onSelect(info);
    }
  } else if (!selected) {
    props.onSelect(info);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onKeyDown"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onKeyDown (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onKeyDown)
- description and source-code
```javascript
function onKeyDown(e) {
  var keyCode = e.keyCode;
  if (keyCode === _KeyCode2["default"].ENTER) {
    this.onClick(e);
    return true;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onMouseEnter)
- description and source-code
```javascript
function onMouseEnter(e) {
  var props = this.props;
  var eventKey = props.eventKey,
      parentMenu = props.parentMenu;

  this.clearMenuItemMouseLeaveTimer(parentMenu.menuItemInstance !== this);
  if (parentMenu.subMenuInstance) {
    parentMenu.subMenuInstance.clearSubMenuTimers();
  }
  props.onItemHover({
    key: eventKey,
    item: this,
    hover: true,
    domEvent: e,
    trigger: 'mouseenter'
  });
  props.onMouseEnter({
    key: eventKey,
    domEvent: e
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Menu.Item.prototype.__reactAutoBindMap.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.Item.prototype.__reactAutoBindMap.onMouseLeave)
- description and source-code
```javascript
function onMouseLeave(e) {
  var _this = this;

  var props = this.props;
  var eventKey = props.eventKey,
      parentMenu = props.parentMenu;

  parentMenu.menuItemInstance = this;
  parentMenu.menuItemMouseLeaveFn = function () {
    if (_this.isMounted() && props.active) {
      props.onItemHover({
        key: eventKey,
        item: _this,
        hover: false,
        domEvent: e,
        trigger: 'mouseleave'
      });
    }
  };
  parentMenu.menuItemMouseLeaveTimer = setTimeout(parentMenu.menuItemMouseLeaveFn, 30);
  props.onMouseLeave({
    key: eventKey,
    domEvent: e
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.ItemGroup"></a>[module antd.Menu.ItemGroup](#apidoc.module.antd.Menu.ItemGroup)

#### <a name="apidoc.element.antd.Menu.ItemGroup.ItemGroup"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>ItemGroup (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup.ItemGroup)
- description and source-code
```javascript
ItemGroup = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.ItemGroup.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.</span>getDefaultProps ()](#apidoc.element.antd.Menu.ItemGroup.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    disabled: true
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.ItemGroup.prototype"></a>[module antd.Menu.ItemGroup.prototype](#apidoc.module.antd.Menu.ItemGroup.prototype)

#### <a name="apidoc.element.antd.Menu.ItemGroup.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.ItemGroup.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.ItemGroup.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.ItemGroup.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.ItemGroup.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>render ()](#apidoc.element.antd.Menu.ItemGroup.prototype.render)
- description and source-code
```javascript
function render() {
  var props = this.props;
  var _props$className = props.className,
      className = _props$className === undefined ? '' : _props$className,
      rootPrefixCls = props.rootPrefixCls;

  var titleClassName = rootPrefixCls + '-item-group-title';
  var listClassName = rootPrefixCls + '-item-group-list';
  return _react2["default"].createElement(
    'li',
    { className: className + ' ' + rootPrefixCls + '-item-group' },
    _react2["default"].createElement(
      'div',
      { className: titleClassName },
      props.title
    ),
    _react2["default"].createElement(
      'ul',
      { className: listClassName },
      _react2["default"].Children.map(props.children, this.renderInnerMenuItem)
    )
  );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Menu.ItemGroup.prototype.renderInnerMenuItem"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.</span>renderInnerMenuItem (item, subIndex)](#apidoc.element.antd.Menu.ItemGroup.prototype.renderInnerMenuItem)
- description and source-code
```javascript
function renderInnerMenuItem(item, subIndex) {
  var _props = this.props,
      renderMenuItem = _props.renderMenuItem,
      index = _props.index;

  return renderMenuItem(item, index, subIndex);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.ItemGroup.prototype.__reactAutoBindMap"></a>[module antd.Menu.ItemGroup.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.ItemGroup.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.Menu.ItemGroup.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.ItemGroup.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.ItemGroup.prototype.__reactAutoBindMap.renderInnerMenuItem"></a>[function <span class="apidocSignatureSpan">antd.Menu.ItemGroup.prototype.__reactAutoBindMap.</span>renderInnerMenuItem (item, subIndex)](#apidoc.element.antd.Menu.ItemGroup.prototype.__reactAutoBindMap.renderInnerMenuItem)
- description and source-code
```javascript
function renderInnerMenuItem(item, subIndex) {
  var _props = this.props,
      renderMenuItem = _props.renderMenuItem,
      index = _props.index;

  return renderMenuItem(item, index, subIndex);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.SubMenu"></a>[module antd.Menu.SubMenu](#apidoc.module.antd.Menu.SubMenu)

#### <a name="apidoc.element.antd.Menu.SubMenu.SubMenu"></a>[function <span class="apidocSignatureSpan">antd.Menu.</span>SubMenu (props, context, updater)](#apidoc.element.antd.Menu.SubMenu.SubMenu)
- description and source-code
```javascript
SubMenu = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.</span>getDefaultProps ()](#apidoc.element.antd.Menu.SubMenu.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    onMouseEnter: _util.noop,
    onMouseLeave: _util.noop,
    onTitleMouseEnter: _util.noop,
    onTitleMouseLeave: _util.noop,
    onTitleClick: _util.noop,
    title: ''
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.SubMenu.prototype"></a>[module antd.Menu.SubMenu.prototype](#apidoc.module.antd.Menu.SubMenu.prototype)

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.addKeyPath"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>addKeyPath (info)](#apidoc.element.antd.Menu.SubMenu.prototype.addKeyPath)
- description and source-code
```javascript
function addKeyPath(info) {
  return (0, _extends3["default"])({}, info, {
    keyPath: (info.keyPath || []).concat(this.props.eventKey)
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.bindRootCloseHandlers"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>bindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.bindRootCloseHandlers)
- description and source-code
```javascript
function bindRootCloseHandlers() {
  if (!this._onDocumentClickListener) {
    this._onDocumentClickListener = (0, _addEventListener2["default"])(document, 'click', this.handleDocumentClick);
    this._onDocumentKeyupListener = (0, _addEventListener2["default"])(document, 'keyup', this.handleDocumentKeyUp);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuLeaveTimer"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>clearSubMenuLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuLeaveTimer)
- description and source-code
```javascript
function clearSubMenuLeaveTimer() {
  var callFn = void 0;
  var parentMenu = this.props.parentMenu;
  if (parentMenu.subMenuLeaveTimer) {
    clearTimeout(parentMenu.subMenuLeaveTimer);
    parentMenu.subMenuLeaveTimer = null;
    if (callFn && parentMenu.subMenuLeaveFn) {
      parentMenu.subMenuLeaveFn();
    }
    parentMenu.subMenuLeaveFn = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuTimers"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>clearSubMenuTimers ()](#apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuTimers)
- description and source-code
```javascript
function clearSubMenuTimers() {
  var callFn = void 0;
  this.clearSubMenuLeaveTimer(callFn);
  this.clearSubMenuTitleLeaveTimer(callFn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuTitleLeaveTimer"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>clearSubMenuTitleLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.clearSubMenuTitleLeaveTimer)
- description and source-code
```javascript
function clearSubMenuTitleLeaveTimer() {
  var callFn = void 0;
  var parentMenu = this.props.parentMenu;
  if (parentMenu.subMenuTitleLeaveTimer) {
    clearTimeout(parentMenu.subMenuTitleLeaveTimer);
    parentMenu.subMenuTitleLeaveTimer = null;
    if (callFn && parentMenu.subMenuTitleLeaveFn) {
      parentMenu.subMenuTitleLeaveFn();
    }
    parentMenu.subMenuTitleLeaveFn = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentDidMount ()](#apidoc.element.antd.Menu.SubMenu.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this.componentDidUpdate();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentDidUpdate ()](#apidoc.element.antd.Menu.SubMenu.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {
  if (this.props.mode !== 'inline') {
    if (this.props.open) {
      this.bindRootCloseHandlers();
    } else {
      this.unbindRootCloseHandlers();
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Menu.SubMenu.prototype.componentWillUnmount)
- description and source-code
```javascript
function chainedFunction() {
  one.apply(this, arguments);
  two.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Menu.SubMenu.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getActiveClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getActiveClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getActiveClassName)
- description and source-code
```javascript
function getActiveClassName() {
  return this.getPrefixCls() + '-active';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getDOMNode ()](#apidoc.element.antd.Menu.SubMenu.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getDisabledClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getDisabledClassName)
- description and source-code
```javascript
function getDisabledClassName() {
  return this.getPrefixCls() + '-disabled';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getInitialState"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getInitialState ()](#apidoc.element.antd.Menu.SubMenu.prototype.getInitialState)
- description and source-code
```javascript
function getInitialState() {
  this.isSubMenu = 1;
  return {
    defaultActiveFirst: false
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getOpenClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getOpenClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getOpenClassName)
- description and source-code
```javascript
function getOpenClassName() {
  return this.props.rootPrefixCls + '-submenu-open';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getPrefixCls"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getPrefixCls ()](#apidoc.element.antd.Menu.SubMenu.prototype.getPrefixCls)
- description and source-code
```javascript
function getPrefixCls() {
  return this.props.rootPrefixCls + '-submenu';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.getSelectedClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.getSelectedClassName)
- description and source-code
```javascript
function getSelectedClassName() {
  return this.getPrefixCls() + '-selected';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.handleDocumentClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>handleDocumentClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.handleDocumentClick)
- description and source-code
```javascript
function handleDocumentClick(e) {
  // If the click originated from within this component
  // don't do anything.
  if ((0, _contains2["default"])(_reactDom2["default"].findDOMNode(this), e.target)) {
    return;
  }
  var props = this.props;
  props.onItemHover({
    hover: false,
    item: this,
    key: this.props.eventKey
  });
  this.triggerOpenChange(false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.handleDocumentKeyUp"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>handleDocumentKeyUp (e)](#apidoc.element.antd.Menu.SubMenu.prototype.handleDocumentKeyUp)
- description and source-code
```javascript
function handleDocumentKeyUp(e) {
  if (e.keyCode === _KeyCode2["default"].ESC) {
    this.props.onItemHover({
      key: this.props.eventKey,
      item: this,
      hover: false
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.isChildrenSelected"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>isChildrenSelected ()](#apidoc.element.antd.Menu.SubMenu.prototype.isChildrenSelected)
- description and source-code
```javascript
function isChildrenSelected() {
  var ret = { find: false };
  (0, _util.loopMenuItemRecusively)(this.props.children, this.props.selectedKeys, ret);
  return ret.find;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.isOpen"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>isOpen ()](#apidoc.element.antd.Menu.SubMenu.prototype.isOpen)
- description and source-code
```javascript
function isOpen() {
  return this.props.openKeys.indexOf(this.props.eventKey) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onDeselect"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onDeselect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.onDeselect)
- description and source-code
```javascript
function onDeselect(info) {
  this.props.onDeselect(info);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onDestroy"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onDestroy (key)](#apidoc.element.antd.Menu.SubMenu.prototype.onDestroy)
- description and source-code
```javascript
function onDestroy(key) {
  this.props.onDestroy(key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onKeyDown"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onKeyDown (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onKeyDown)
- description and source-code
```javascript
function onKeyDown(e) {
  var keyCode = e.keyCode;
  var menu = this.menuInstance;
  var isOpen = this.isOpen();

  if (keyCode === _KeyCode2["default"].ENTER) {
    this.onTitleClick(e);
    this.setState({
      defaultActiveFirst: true
    });
    return true;
  }

  if (keyCode === _KeyCode2["default"].RIGHT) {
    if (isOpen) {
      menu.onKeyDown(e);
    } else {
      this.triggerOpenChange(true);
      this.setState({
        defaultActiveFirst: true
      });
    }
    return true;
  }
  if (keyCode === _KeyCode2["default"].LEFT) {
    var handled = void 0;
    if (isOpen) {
      handled = menu.onKeyDown(e);
    } else {
      return undefined;
    }
    if (!handled) {
      this.triggerOpenChange(false);
      handled = true;
    }
    return handled;
  }

  if (isOpen && (keyCode === _KeyCode2["default"].UP || keyCode === _KeyCode2["default"].DOWN)) {
    return menu.onKeyDown(e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onMouseEnter)
- description and source-code
```javascript
function onMouseEnter(e) {
  var props = this.props;
  this.clearSubMenuLeaveTimer(props.parentMenu.subMenuInstance !== this);
  props.onMouseEnter({
    key: props.eventKey,
    domEvent: e
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onMouseLeave)
- description and source-code
```javascript
function onMouseLeave(e) {
  var _this2 = this;

  var props = this.props;
  var parentMenu = props.parentMenu,
      eventKey = props.eventKey;

  parentMenu.subMenuInstance = this;
  parentMenu.subMenuLeaveFn = function () {
    if (_this2.isMounted()) {
      // leave whole sub tree
      // still active
      if (props.mode !== 'inline') {
        var isOpen = _this2.isOpen();
        if (isOpen && props.closeSubMenuOnMouseLeave && props.active) {
          props.onItemHover({
            key: eventKey,
            item: _this2,
            hover: false,
            trigger: 'mouseleave',
            openChanges: [{
              key: eventKey,
              item: _this2,
              trigger: 'mouseleave',
              open: false
            }]
          });
        } else {
          if (props.active) {
            props.onItemHover({
              key: eventKey,
              item: _this2,
              hover: false,
              trigger: 'mouseleave'
            });
          }
          if (isOpen && props.closeSubMenuOnMouseLeave) {
            _this2.triggerOpenChange(false);
          }
        }
      }
      // trigger mouseleave
      props.onMouseLeave({
        key: eventKey,
        domEvent: e
      });
    }
  };
  // prevent popup menu and submenu gap
  parentMenu.subMenuLeaveTimer = setTimeout(parentMenu.subMenuLeaveFn, 100);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onOpenChange"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onOpenChange (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onOpenChange)
- description and source-code
```javascript
function onOpenChange(e) {
  this.props.onOpenChange(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onSelect"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onSelect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.onSelect)
- description and source-code
```javascript
function onSelect(info) {
  this.props.onSelect(info);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onSubMenuClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onSubMenuClick (info)](#apidoc.element.antd.Menu.SubMenu.prototype.onSubMenuClick)
- description and source-code
```javascript
function onSubMenuClick(info) {
  this.props.onClick(this.addKeyPath(info));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onTitleClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onTitleClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onTitleClick)
- description and source-code
```javascript
function onTitleClick(e) {
  var props = this.props;

  props.onTitleClick({
    key: props.eventKey,
    domEvent: e
  });
  if (props.openSubMenuOnMouseEnter) {
    return;
  }
  this.triggerOpenChange(!this.isOpen(), 'click');
  this.setState({
    defaultActiveFirst: false
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onTitleMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onTitleMouseEnter (domEvent)](#apidoc.element.antd.Menu.SubMenu.prototype.onTitleMouseEnter)
- description and source-code
```javascript
function onTitleMouseEnter(domEvent) {
  var props = this.props;
  var parentMenu = props.parentMenu,
      key = props.eventKey;

  var item = this;
  this.clearSubMenuTitleLeaveTimer(parentMenu.subMenuInstance !== item);
  if (parentMenu.menuItemInstance) {
    parentMenu.menuItemInstance.clearMenuItemMouseLeaveTimer(true);
  }
  var openChanges = [];
  if (props.openSubMenuOnMouseEnter) {
    openChanges.push({
      key: key,
      item: item,
      trigger: 'mouseenter',
      open: true
    });
  }
  props.onItemHover({
    key: key,
    item: item,
    hover: true,
    trigger: 'mouseenter',
    openChanges: openChanges
  });
  this.setState({
    defaultActiveFirst: false
  });
  props.onTitleMouseEnter({
    key: key,
    domEvent: domEvent
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.onTitleMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>onTitleMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.onTitleMouseLeave)
- description and source-code
```javascript
function onTitleMouseLeave(e) {
  var _this = this;

  var props = this.props;
  var parentMenu = props.parentMenu,
      eventKey = props.eventKey;

  parentMenu.subMenuInstance = this;
  parentMenu.subMenuTitleLeaveFn = function () {
    if (_this.isMounted()) {
      // leave whole sub tree
      // still active
      if (props.mode === 'inline' && props.active) {
        props.onItemHover({
          key: eventKey,
          item: _this,
          hover: false,
          trigger: 'mouseleave'
        });
      }
      props.onTitleMouseLeave({
        key: props.eventKey,
        domEvent: e
      });
    }
  };
  parentMenu.subMenuTitleLeaveTimer = setTimeout(parentMenu.subMenuTitleLeaveFn, 100);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>render ()](#apidoc.element.antd.Menu.SubMenu.prototype.render)
- description and source-code
```javascript
function render() {
  var _classes;

  var isOpen = this.isOpen();
  this.haveOpen = this.haveOpen || isOpen;
  var props = this.props;
  var prefixCls = this.getPrefixCls();
  var classes = (_classes = {}, (0, _defineProperty3["default"])(_classes, props.className, !!props.className), (0, _defineProperty3
["default"])(_classes, prefixCls + '-' + props.mode, 1), _classes);

  classes[this.getOpenClassName()] = isOpen;
  classes[this.getActiveClassName()] = props.active;
  classes[this.getDisabledClassName()] = props.disabled;
  classes[this.getSelectedClassName()] = this.isChildrenSelected();

  if (!this._menuId) {
    if (props.eventKey) {
      this._menuId = props.eventKey + '$Menu';
    } else {
      this._menuId = '$__$' + ++guid + '$Menu';
    }
  }

  classes[prefixCls] = true;
  classes[prefixCls + '-' + props.mode] = 1;
  var titleClickEvents = {};
  var mouseEvents = {};
  var titleMouseEvents = {};
  if (!props.disabled) {
    titleClickEvents = {
      onClick: this.onTitleClick
    };
    mouseEvents = {
      onMouseLeave: this.onMouseLeave,
      onMouseEnter: this.onMouseEnter
    };
    // only works in title, not outer li
    titleMouseEvents = {
      onMouseEnter: this.onTitleMouseEnter,
      onMouseLeave: this.onTitleMouseLeave
    };
  }
  var style = {};
  if (props.mode === 'inline') {
    style.paddingLeft = props.inlineIndent * props.level;
  }
  return _react2["default"].createElement(
    'li',
    (0, _extends3["default"])({ className: (0, _classnames2["default"])(classes) }, mouseEvents),
    _react2["default"].createElement(
      'div',
      (0, _extends3["default"])({
        style: style,
        className: prefixCls + '-title'
      }, titleMouseEvents, titleClickEvents, {
        'aria-expanded': isOpen,
        'aria-owns': this._menuId,
        'aria-haspopup': 'true'
      }),
      props.title
    ),
    this.renderChildren(props.children)
  );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.renderChildren"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>renderChildren (children)](#apidoc.element.antd.Menu.SubMenu.prototype.renderChildren)
- description and source-code
```javascript
function renderChildren(children) {
  var props = this.props;
  var baseProps = {
    mode: props.mode === 'horizontal' ? 'vertical' : props.mode,
    visible: this.isOpen(),
    level: props.level + 1,
    inlineIndent: props.inlineIndent,
    focusable: false,
    onClick: this.onSubMenuClick,
    onSelect: this.onSelect,
    onDeselect: this.onDeselect,
    onDestroy: this.onDestroy,
    selectedKeys: props.selectedKeys,
    eventKey: props.eventKey + '-menu-',
    openKeys: props.openKeys,
    openTransitionName: props.openTransitionName,
    openAnimation: props.openAnimation,
    onOpenChange: this.onOpenChange,
    closeSubMenuOnMouseLeave: props.closeSubMenuOnMouseLeave,
    defaultActiveFirst: this.state.defaultActiveFirst,
    multiple: props.multiple,
    prefixCls: props.rootPrefixCls,
    id: this._menuId,
    ref: this.saveMenuInstance
  };
  return _react2["default"].createElement(
    _SubPopupMenu2["default"],
    baseProps,
    children
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.saveMenuInstance"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>saveMenuInstance (c)](#apidoc.element.antd.Menu.SubMenu.prototype.saveMenuInstance)
- description and source-code
```javascript
function saveMenuInstance(c) {
  this.menuInstance = c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.triggerOpenChange"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>triggerOpenChange (open, type)](#apidoc.element.antd.Menu.SubMenu.prototype.triggerOpenChange)
- description and source-code
```javascript
function triggerOpenChange(open, type) {
  var key = this.props.eventKey;
  this.onOpenChange({
    key: key,
    item: this,
    trigger: type,
    open: open
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.unbindRootCloseHandlers"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.</span>unbindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.unbindRootCloseHandlers)
- description and source-code
```javascript
function unbindRootCloseHandlers() {
  if (this._onDocumentClickListener) {
    this._onDocumentClickListener.remove();
    this._onDocumentClickListener = null;
  }

  if (this._onDocumentKeyupListener) {
    this._onDocumentKeyupListener.remove();
    this._onDocumentKeyupListener = null;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.SubMenu.prototype.__reactAutoBindMap"></a>[module antd.Menu.SubMenu.prototype.__reactAutoBindMap](#apidoc.module.antd.Menu.SubMenu.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.addKeyPath"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>addKeyPath (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.addKeyPath)
- description and source-code
```javascript
function addKeyPath(info) {
  return (0, _extends3["default"])({}, info, {
    keyPath: (info.keyPath || []).concat(this.props.eventKey)
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.bindRootCloseHandlers"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>bindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.bindRootCloseHandlers)
- description and source-code
```javascript
function bindRootCloseHandlers() {
  if (!this._onDocumentClickListener) {
    this._onDocumentClickListener = (0, _addEventListener2["default"])(document, 'click', this.handleDocumentClick);
    this._onDocumentKeyupListener = (0, _addEventListener2["default"])(document, 'keyup', this.handleDocumentKeyUp);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuLeaveTimer"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>clearSubMenuLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuLeaveTimer)
- description and source-code
```javascript
function clearSubMenuLeaveTimer() {
  var callFn = void 0;
  var parentMenu = this.props.parentMenu;
  if (parentMenu.subMenuLeaveTimer) {
    clearTimeout(parentMenu.subMenuLeaveTimer);
    parentMenu.subMenuLeaveTimer = null;
    if (callFn && parentMenu.subMenuLeaveFn) {
      parentMenu.subMenuLeaveFn();
    }
    parentMenu.subMenuLeaveFn = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuTimers"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>clearSubMenuTimers ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuTimers)
- description and source-code
```javascript
function clearSubMenuTimers() {
  var callFn = void 0;
  this.clearSubMenuLeaveTimer(callFn);
  this.clearSubMenuTitleLeaveTimer(callFn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuTitleLeaveTimer"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>clearSubMenuTitleLeaveTimer ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.clearSubMenuTitleLeaveTimer)
- description and source-code
```javascript
function clearSubMenuTitleLeaveTimer() {
  var callFn = void 0;
  var parentMenu = this.props.parentMenu;
  if (parentMenu.subMenuTitleLeaveTimer) {
    clearTimeout(parentMenu.subMenuTitleLeaveTimer);
    parentMenu.subMenuTitleLeaveTimer = null;
    if (callFn && parentMenu.subMenuTitleLeaveFn) {
      parentMenu.subMenuTitleLeaveFn();
    }
    parentMenu.subMenuTitleLeaveFn = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getActiveClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getActiveClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getActiveClassName)
- description and source-code
```javascript
function getActiveClassName() {
  return this.getPrefixCls() + '-active';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getDisabledClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getDisabledClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getDisabledClassName)
- description and source-code
```javascript
function getDisabledClassName() {
  return this.getPrefixCls() + '-disabled';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getOpenClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getOpenClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getOpenClassName)
- description and source-code
```javascript
function getOpenClassName() {
  return this.props.rootPrefixCls + '-submenu-open';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getPrefixCls"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getPrefixCls ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getPrefixCls)
- description and source-code
```javascript
function getPrefixCls() {
  return this.props.rootPrefixCls + '-submenu';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getSelectedClassName"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>getSelectedClassName ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.getSelectedClassName)
- description and source-code
```javascript
function getSelectedClassName() {
  return this.getPrefixCls() + '-selected';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.handleDocumentClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>handleDocumentClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.handleDocumentClick)
- description and source-code
```javascript
function handleDocumentClick(e) {
  // If the click originated from within this component
  // don't do anything.
  if ((0, _contains2["default"])(_reactDom2["default"].findDOMNode(this), e.target)) {
    return;
  }
  var props = this.props;
  props.onItemHover({
    hover: false,
    item: this,
    key: this.props.eventKey
  });
  this.triggerOpenChange(false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.handleDocumentKeyUp"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>handleDocumentKeyUp (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.handleDocumentKeyUp)
- description and source-code
```javascript
function handleDocumentKeyUp(e) {
  if (e.keyCode === _KeyCode2["default"].ESC) {
    this.props.onItemHover({
      key: this.props.eventKey,
      item: this,
      hover: false
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.isChildrenSelected"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>isChildrenSelected ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.isChildrenSelected)
- description and source-code
```javascript
function isChildrenSelected() {
  var ret = { find: false };
  (0, _util.loopMenuItemRecusively)(this.props.children, this.props.selectedKeys, ret);
  return ret.find;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.isOpen"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>isOpen ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.isOpen)
- description and source-code
```javascript
function isOpen() {
  return this.props.openKeys.indexOf(this.props.eventKey) !== -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onDeselect"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onDeselect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onDeselect)
- description and source-code
```javascript
function onDeselect(info) {
  this.props.onDeselect(info);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onDestroy"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onDestroy (key)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onDestroy)
- description and source-code
```javascript
function onDestroy(key) {
  this.props.onDestroy(key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onKeyDown"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onKeyDown (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onKeyDown)
- description and source-code
```javascript
function onKeyDown(e) {
  var keyCode = e.keyCode;
  var menu = this.menuInstance;
  var isOpen = this.isOpen();

  if (keyCode === _KeyCode2["default"].ENTER) {
    this.onTitleClick(e);
    this.setState({
      defaultActiveFirst: true
    });
    return true;
  }

  if (keyCode === _KeyCode2["default"].RIGHT) {
    if (isOpen) {
      menu.onKeyDown(e);
    } else {
      this.triggerOpenChange(true);
      this.setState({
        defaultActiveFirst: true
      });
    }
    return true;
  }
  if (keyCode === _KeyCode2["default"].LEFT) {
    var handled = void 0;
    if (isOpen) {
      handled = menu.onKeyDown(e);
    } else {
      return undefined;
    }
    if (!handled) {
      this.triggerOpenChange(false);
      handled = true;
    }
    return handled;
  }

  if (isOpen && (keyCode === _KeyCode2["default"].UP || keyCode === _KeyCode2["default"].DOWN)) {
    return menu.onKeyDown(e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onMouseEnter (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onMouseEnter)
- description and source-code
```javascript
function onMouseEnter(e) {
  var props = this.props;
  this.clearSubMenuLeaveTimer(props.parentMenu.subMenuInstance !== this);
  props.onMouseEnter({
    key: props.eventKey,
    domEvent: e
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onMouseLeave)
- description and source-code
```javascript
function onMouseLeave(e) {
  var _this2 = this;

  var props = this.props;
  var parentMenu = props.parentMenu,
      eventKey = props.eventKey;

  parentMenu.subMenuInstance = this;
  parentMenu.subMenuLeaveFn = function () {
    if (_this2.isMounted()) {
      // leave whole sub tree
      // still active
      if (props.mode !== 'inline') {
        var isOpen = _this2.isOpen();
        if (isOpen && props.closeSubMenuOnMouseLeave && props.active) {
          props.onItemHover({
            key: eventKey,
            item: _this2,
            hover: false,
            trigger: 'mouseleave',
            openChanges: [{
              key: eventKey,
              item: _this2,
              trigger: 'mouseleave',
              open: false
            }]
          });
        } else {
          if (props.active) {
            props.onItemHover({
              key: eventKey,
              item: _this2,
              hover: false,
              trigger: 'mouseleave'
            });
          }
          if (isOpen && props.closeSubMenuOnMouseLeave) {
            _this2.triggerOpenChange(false);
          }
        }
      }
      // trigger mouseleave
      props.onMouseLeave({
        key: eventKey,
        domEvent: e
      });
    }
  };
  // prevent popup menu and submenu gap
  parentMenu.subMenuLeaveTimer = setTimeout(parentMenu.subMenuLeaveFn, 100);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onOpenChange"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onOpenChange (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onOpenChange)
- description and source-code
```javascript
function onOpenChange(e) {
  this.props.onOpenChange(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onSelect"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onSelect (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onSelect)
- description and source-code
```javascript
function onSelect(info) {
  this.props.onSelect(info);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onSubMenuClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onSubMenuClick (info)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onSubMenuClick)
- description and source-code
```javascript
function onSubMenuClick(info) {
  this.props.onClick(this.addKeyPath(info));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleClick"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onTitleClick (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleClick)
- description and source-code
```javascript
function onTitleClick(e) {
  var props = this.props;

  props.onTitleClick({
    key: props.eventKey,
    domEvent: e
  });
  if (props.openSubMenuOnMouseEnter) {
    return;
  }
  this.triggerOpenChange(!this.isOpen(), 'click');
  this.setState({
    defaultActiveFirst: false
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onTitleMouseEnter (domEvent)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleMouseEnter)
- description and source-code
```javascript
function onTitleMouseEnter(domEvent) {
  var props = this.props;
  var parentMenu = props.parentMenu,
      key = props.eventKey;

  var item = this;
  this.clearSubMenuTitleLeaveTimer(parentMenu.subMenuInstance !== item);
  if (parentMenu.menuItemInstance) {
    parentMenu.menuItemInstance.clearMenuItemMouseLeaveTimer(true);
  }
  var openChanges = [];
  if (props.openSubMenuOnMouseEnter) {
    openChanges.push({
      key: key,
      item: item,
      trigger: 'mouseenter',
      open: true
    });
  }
  props.onItemHover({
    key: key,
    item: item,
    hover: true,
    trigger: 'mouseenter',
    openChanges: openChanges
  });
  this.setState({
    defaultActiveFirst: false
  });
  props.onTitleMouseEnter({
    key: key,
    domEvent: domEvent
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>onTitleMouseLeave (e)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.onTitleMouseLeave)
- description and source-code
```javascript
function onTitleMouseLeave(e) {
  var _this = this;

  var props = this.props;
  var parentMenu = props.parentMenu,
      eventKey = props.eventKey;

  parentMenu.subMenuInstance = this;
  parentMenu.subMenuTitleLeaveFn = function () {
    if (_this.isMounted()) {
      // leave whole sub tree
      // still active
      if (props.mode === 'inline' && props.active) {
        props.onItemHover({
          key: eventKey,
          item: _this,
          hover: false,
          trigger: 'mouseleave'
        });
      }
      props.onTitleMouseLeave({
        key: props.eventKey,
        domEvent: e
      });
    }
  };
  parentMenu.subMenuTitleLeaveTimer = setTimeout(parentMenu.subMenuTitleLeaveFn, 100);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.renderChildren"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>renderChildren (children)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.renderChildren)
- description and source-code
```javascript
function renderChildren(children) {
  var props = this.props;
  var baseProps = {
    mode: props.mode === 'horizontal' ? 'vertical' : props.mode,
    visible: this.isOpen(),
    level: props.level + 1,
    inlineIndent: props.inlineIndent,
    focusable: false,
    onClick: this.onSubMenuClick,
    onSelect: this.onSelect,
    onDeselect: this.onDeselect,
    onDestroy: this.onDestroy,
    selectedKeys: props.selectedKeys,
    eventKey: props.eventKey + '-menu-',
    openKeys: props.openKeys,
    openTransitionName: props.openTransitionName,
    openAnimation: props.openAnimation,
    onOpenChange: this.onOpenChange,
    closeSubMenuOnMouseLeave: props.closeSubMenuOnMouseLeave,
    defaultActiveFirst: this.state.defaultActiveFirst,
    multiple: props.multiple,
    prefixCls: props.rootPrefixCls,
    id: this._menuId,
    ref: this.saveMenuInstance
  };
  return _react2["default"].createElement(
    _SubPopupMenu2["default"],
    baseProps,
    children
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.saveMenuInstance"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>saveMenuInstance (c)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.saveMenuInstance)
- description and source-code
```javascript
function saveMenuInstance(c) {
  this.menuInstance = c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.triggerOpenChange"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>triggerOpenChange (open, type)](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.triggerOpenChange)
- description and source-code
```javascript
function triggerOpenChange(open, type) {
  var key = this.props.eventKey;
  this.onOpenChange({
    key: key,
    item: this,
    trigger: type,
    open: open
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.unbindRootCloseHandlers"></a>[function <span class="apidocSignatureSpan">antd.Menu.SubMenu.prototype.__reactAutoBindMap.</span>unbindRootCloseHandlers ()](#apidoc.element.antd.Menu.SubMenu.prototype.__reactAutoBindMap.unbindRootCloseHandlers)
- description and source-code
```javascript
function unbindRootCloseHandlers() {
  if (this._onDocumentClickListener) {
    this._onDocumentClickListener.remove();
    this._onDocumentClickListener = null;
  }

  if (this._onDocumentKeyupListener) {
    this._onDocumentKeyupListener.remove();
    this._onDocumentKeyupListener = null;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Menu.prototype"></a>[module antd.Menu.prototype](#apidoc.module.antd.Menu.prototype)

#### <a name="apidoc.element.antd.Menu.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Menu.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Menu.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if (this.props.mode === 'inline' && nextProps.mode !== 'inline') {
        this.switchModeFromInline = true;
    }
    if ('openKeys' in nextProps) {
        this.setState({ openKeys: nextProps.openKeys });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Menu.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Menu.prototype.</span>render ()](#apidoc.element.antd.Menu.prototype.render)
- description and source-code
```javascript
function render() {
    var openAnimation = this.props.openAnimation || this.props.openTransitionName;
    if (this.props.openAnimation === undefined && this.props.openTransitionName === undefined) {
        switch (this.props.mode) {
            case 'horizontal':
                openAnimation = 'slide-up';
                break;
            case 'vertical':
                // When mode switch from inline
                // submenu should hide without animation
                if (this.switchModeFromInline) {
                    openAnimation = '';
                    this.switchModeFromInline = false;
                } else {
                    openAnimation = 'zoom-big';
                }
                break;
            case 'inline':
                openAnimation = _openAnimation2["default"];
                break;
            default:
        }
    }
    var props = {};
    var className = this.props.className + ' ' + this.props.prefixCls + '-' + this.props.theme;
    if (this.props.mode !== 'inline') {
        // There is this.state.openKeys for
        // closing vertical popup submenu after click it
        props = {
            openKeys: this.state.openKeys,
            onClick: this.handleClick,
            onOpenChange: this.handleOpenChange,
            openTransitionName: openAnimation,
            className: className
        };
    } else {
        props = {
            openAnimation: openAnimation,
            className: className
        };
    }
    return _react2["default"].createElement(_rcMenu2["default"], (0, _extends3["default"])({}, this.props, props));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Menu.prototype.setOpenKeys"></a>[function <span class="apidocSignatureSpan">antd.Menu.prototype.</span>setOpenKeys (openKeys)](#apidoc.element.antd.Menu.prototype.setOpenKeys)
- description and source-code
```javascript
function setOpenKeys(openKeys) {
    if (!('openKeys' in this.props)) {
        this.setState({ openKeys: openKeys });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Modal"></a>[module antd.Modal](#apidoc.module.antd.Modal)

#### <a name="apidoc.element.antd.Modal.Modal"></a>[function <span class="apidocSignatureSpan">antd.</span>Modal ()](#apidoc.element.antd.Modal.Modal)
- description and source-code
```javascript
function Modal() {
    (0, _classCallCheck3["default"])(this, Modal);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.handleCancel = function (e) {
        var onCancel = _this.props.onCancel;
        if (onCancel) {
            onCancel(e);
        }
    };
    _this.handleOk = function (e) {
        var onOk = _this.props.onOk;
        if (onOk) {
            onOk(e);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.confirm"></a>[function <span class="apidocSignatureSpan">antd.Modal.</span>confirm (props)](#apidoc.element.antd.Modal.confirm)
- description and source-code
```javascript
confirm = function (props) {
    var config = (0, _objectAssign2["default"])({}, {
        type: 'confirm',
        okCancel: true
    }, props);
    return (0, _confirm2["default"])(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.error"></a>[function <span class="apidocSignatureSpan">antd.Modal.</span>error (props)](#apidoc.element.antd.Modal.error)
- description and source-code
```javascript
error = function (props) {
    var config = (0, _objectAssign2["default"])({}, {
        type: 'error',
        iconType: 'cross-circle',
        okCancel: false
    }, props);
    return (0, _confirm2["default"])(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.info"></a>[function <span class="apidocSignatureSpan">antd.Modal.</span>info (props)](#apidoc.element.antd.Modal.info)
- description and source-code
```javascript
info = function (props) {
    var config = (0, _objectAssign2["default"])({}, {
        type: 'info',
        iconType: 'info-circle',
        okCancel: false
    }, props);
    return (0, _confirm2["default"])(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.success"></a>[function <span class="apidocSignatureSpan">antd.Modal.</span>success (props)](#apidoc.element.antd.Modal.success)
- description and source-code
```javascript
success = function (props) {
    var config = (0, _objectAssign2["default"])({}, {
        type: 'success',
        iconType: 'check-circle',
        okCancel: false
    }, props);
    return (0, _confirm2["default"])(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.warn"></a>[function <span class="apidocSignatureSpan">antd.Modal.</span>warn (props)](#apidoc.element.antd.Modal.warn)
- description and source-code
```javascript
warn = function (props) {
    var config = (0, _objectAssign2["default"])({}, {
        type: 'warning',
        iconType: 'exclamation-circle',
        okCancel: false
    }, props);
    return (0, _confirm2["default"])(config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.warning"></a>[function <span class="apidocSignatureSpan">antd.Modal.</span>warning (props)](#apidoc.element.antd.Modal.warning)
- description and source-code
```javascript
warning = function (props) {
    var config = (0, _objectAssign2["default"])({}, {
        type: 'warning',
        iconType: 'exclamation-circle',
        okCancel: false
    }, props);
    return (0, _confirm2["default"])(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Modal.contextTypes"></a>[module antd.Modal.contextTypes](#apidoc.module.antd.Modal.contextTypes)

#### <a name="apidoc.element.antd.Modal.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Modal.contextTypes.</span>antLocale ()](#apidoc.element.antd.Modal.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Modal.propTypes"></a>[module antd.Modal.propTypes](#apidoc.module.antd.Modal.propTypes)

#### <a name="apidoc.element.antd.Modal.propTypes.align"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>align ()](#apidoc.element.antd.Modal.propTypes.align)
- description and source-code
```javascript
align = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.cancelText"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>cancelText ()](#apidoc.element.antd.Modal.propTypes.cancelText)
- description and source-code
```javascript
cancelText = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.closable"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>closable ()](#apidoc.element.antd.Modal.propTypes.closable)
- description and source-code
```javascript
closable = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.confirmLoading"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>confirmLoading ()](#apidoc.element.antd.Modal.propTypes.confirmLoading)
- description and source-code
```javascript
confirmLoading = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.footer"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>footer ()](#apidoc.element.antd.Modal.propTypes.footer)
- description and source-code
```javascript
footer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.okText"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>okText ()](#apidoc.element.antd.Modal.propTypes.okText)
- description and source-code
```javascript
okText = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.onCancel"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>onCancel ()](#apidoc.element.antd.Modal.propTypes.onCancel)
- description and source-code
```javascript
onCancel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.onOk"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>onOk ()](#apidoc.element.antd.Modal.propTypes.onOk)
- description and source-code
```javascript
onOk = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>prefixCls ()](#apidoc.element.antd.Modal.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.title"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>title ()](#apidoc.element.antd.Modal.propTypes.title)
- description and source-code
```javascript
title = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.visible"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>visible ()](#apidoc.element.antd.Modal.propTypes.visible)
- description and source-code
```javascript
visible = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.propTypes.width"></a>[function <span class="apidocSignatureSpan">antd.Modal.propTypes.</span>width ()](#apidoc.element.antd.Modal.propTypes.width)
- description and source-code
```javascript
width = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Modal.prototype"></a>[module antd.Modal.prototype](#apidoc.module.antd.Modal.prototype)

#### <a name="apidoc.element.antd.Modal.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Modal.prototype.</span>componentDidMount ()](#apidoc.element.antd.Modal.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    if (mousePositionEventBinded) {
        return;
    }
    // 只有点击事件支持从鼠标位置动画展开
    (0, _addEventListener2["default"])(document.documentElement, 'click', function (e) {
        mousePosition = {
            x: e.pageX,
            y: e.pageY
        };
        // 100ms 内发生过点击事件，则从点击位置动画展示
        // 否则直接 zoom 展示
        // 这样可以兼容非点击方式展开
        setTimeout(function () {
            return mousePosition = null;
        }, 100);
    });
    mousePositionEventBinded = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Modal.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Modal.prototype.</span>render ()](#apidoc.element.antd.Modal.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        okText = _props.okText,
        cancelText = _props.cancelText,
        confirmLoading = _props.confirmLoading,
        footer = _props.footer,
        visible = _props.visible;

    if (this.context.antLocale && this.context.antLocale.Modal) {
        okText = okText || this.context.antLocale.Modal.okText;
        cancelText = cancelText || this.context.antLocale.Modal.cancelText;
    }
    var defaultFooter = [_react2["default"].createElement(
        _button2["default"],
        { key: 'cancel', size: 'large', onClick: this.handleCancel },
        cancelText || '取消'
    ), _react2["default"].createElement(
        _button2["default"],
        { key: 'confirm', type: 'primary', size: 'large', loading: confirmLoading, onClick: this.handleOk },
        okText || '确定'
    )];
    return _react2["default"].createElement(_rcDialog2["default"], (0, _extends3["default"])({ onClose: this.handleCancel, footer
: footer === undefined ? defaultFooter : footer }, this.props, { visible: visible, mousePosition: mousePosition }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Pagination"></a>[module antd.Pagination](#apidoc.module.antd.Pagination)

#### <a name="apidoc.element.antd.Pagination.Pagination"></a>[function <span class="apidocSignatureSpan">antd.</span>Pagination ()](#apidoc.element.antd.Pagination.Pagination)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Pagination.contextTypes"></a>[module antd.Pagination.contextTypes](#apidoc.module.antd.Pagination.contextTypes)

#### <a name="apidoc.element.antd.Pagination.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Pagination.contextTypes.</span>antLocale ()](#apidoc.element.antd.Pagination.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Pagination.prototype"></a>[module antd.Pagination.prototype](#apidoc.module.antd.Pagination.prototype)

#### <a name="apidoc.element.antd.Pagination.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.Pagination.prototype.</span>getLocale ()](#apidoc.element.antd.Pagination.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var antLocale = this.context.antLocale;

    var localeFromContext = antLocale && antLocale[componentName];
    var localeFromProps = this.props.locale || {};
    return (0, _extends3["default"])({}, defaultLocale, localeFromContext || {}, localeFromProps);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Popconfirm"></a>[module antd.Popconfirm](#apidoc.module.antd.Popconfirm)

#### <a name="apidoc.element.antd.Popconfirm.Popconfirm"></a>[function <span class="apidocSignatureSpan">antd.</span>Popconfirm ()](#apidoc.element.antd.Popconfirm.Popconfirm)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Popconfirm.contextTypes"></a>[module antd.Popconfirm.contextTypes](#apidoc.module.antd.Popconfirm.contextTypes)

#### <a name="apidoc.element.antd.Popconfirm.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Popconfirm.contextTypes.</span>antLocale ()](#apidoc.element.antd.Popconfirm.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Popconfirm.prototype"></a>[module antd.Popconfirm.prototype](#apidoc.module.antd.Popconfirm.prototype)

#### <a name="apidoc.element.antd.Popconfirm.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.Popconfirm.prototype.</span>getLocale ()](#apidoc.element.antd.Popconfirm.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var antLocale = this.context.antLocale;

    var localeFromContext = antLocale && antLocale[componentName];
    var localeFromProps = this.props.locale || {};
    return (0, _extends3["default"])({}, defaultLocale, localeFromContext || {}, localeFromProps);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Popover"></a>[module antd.Popover](#apidoc.module.antd.Popover)

#### <a name="apidoc.element.antd.Popover.Popover"></a>[function <span class="apidocSignatureSpan">antd.</span>Popover ()](#apidoc.element.antd.Popover.Popover)
- description and source-code
```javascript
function Popover() {
    (0, _classCallCheck3["default"])(this, Popover);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Popover.prototype"></a>[module antd.Popover.prototype](#apidoc.module.antd.Popover.prototype)

#### <a name="apidoc.element.antd.Popover.prototype.getOverlay"></a>[function <span class="apidocSignatureSpan">antd.Popover.prototype.</span>getOverlay ()](#apidoc.element.antd.Popover.prototype.getOverlay)
- description and source-code
```javascript
function getOverlay() {
    var _props = this.props,
        title = _props.title,
        prefixCls = _props.prefixCls,
        content = _props.content;

    (0, _warning2["default"])(!('overlay' in this.props), 'Popover[overlay] is removed, please use Popover[content] instead, ' + '
see: http://u.ant.design/popover-content');
    return _react2["default"].createElement(
        'div',
        null,
        title && _react2["default"].createElement(
            'div',
            { className: prefixCls + '-title' },
            title
        ),
        _react2["default"].createElement(
            'div',
            { className: prefixCls + '-inner-content' },
            content
        )
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Popover.prototype.getPopupDomNode"></a>[function <span class="apidocSignatureSpan">antd.Popover.prototype.</span>getPopupDomNode ()](#apidoc.element.antd.Popover.prototype.getPopupDomNode)
- description and source-code
```javascript
function getPopupDomNode() {
    return this.refs.tooltip.getPopupDomNode();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Popover.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Popover.prototype.</span>render ()](#apidoc.element.antd.Popover.prototype.render)
- description and source-code
```javascript
function render() {
    var props = (0, _objectAssign2["default"])({}, this.props);
    delete props.title;
    return _react2["default"].createElement(_tooltip2["default"], (0, _extends3["default"])({}, props, { ref: 'tooltip', overlay
: this.getOverlay() }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Progress"></a>[module antd.Progress](#apidoc.module.antd.Progress)

#### <a name="apidoc.element.antd.Progress.Progress"></a>[function <span class="apidocSignatureSpan">antd.</span>Progress ()](#apidoc.element.antd.Progress.Progress)
- description and source-code
```javascript
function Progress() {
    (0, _classCallCheck3["default"])(this, Progress);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Progress.propTypes"></a>[module antd.Progress.propTypes](#apidoc.module.antd.Progress.propTypes)

#### <a name="apidoc.element.antd.Progress.propTypes.format"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>format ()](#apidoc.element.antd.Progress.propTypes.format)
- description and source-code
```javascript
format = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.gapDegree"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>gapDegree ()](#apidoc.element.antd.Progress.propTypes.gapDegree)
- description and source-code
```javascript
gapDegree = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.percent"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>percent ()](#apidoc.element.antd.Progress.propTypes.percent)
- description and source-code
```javascript
percent = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.showInfo"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>showInfo ()](#apidoc.element.antd.Progress.propTypes.showInfo)
- description and source-code
```javascript
showInfo = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.status"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>status ()](#apidoc.element.antd.Progress.propTypes.status)
- description and source-code
```javascript
status = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.strokeWidth"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>strokeWidth ()](#apidoc.element.antd.Progress.propTypes.strokeWidth)
- description and source-code
```javascript
strokeWidth = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.trailColor"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>trailColor ()](#apidoc.element.antd.Progress.propTypes.trailColor)
- description and source-code
```javascript
trailColor = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.type"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>type ()](#apidoc.element.antd.Progress.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Progress.propTypes.width"></a>[function <span class="apidocSignatureSpan">antd.Progress.propTypes.</span>width ()](#apidoc.element.antd.Progress.propTypes.width)
- description and source-code
```javascript
width = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Progress.prototype"></a>[module antd.Progress.prototype](#apidoc.module.antd.Progress.prototype)

#### <a name="apidoc.element.antd.Progress.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Progress.prototype.</span>render ()](#apidoc.element.antd.Progress.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var props = this.props;

    var prefixCls = props.prefixCls,
        className = props.className,
        _props$percent = props.percent,
        percent = _props$percent === undefined ? 0 : _props$percent,
        status = props.status,
        format = props.format,
        trailColor = props.trailColor,
        type = props.type,
        strokeWidth = props.strokeWidth,
        width = props.width,
        showInfo = props.showInfo,
        _props$gapDegree = props.gapDegree,
        gapDegree = _props$gapDegree === undefined ? 0 : _props$gapDegree,
        gapPosition = props.gapPosition,
        restProps = __rest(props, ["prefixCls", "className", "percent", "status", "format", "trailColor", "type", "strokeWidth", "
width", "showInfo", "gapDegree", "gapPosition"]);

    var progressStatus = parseInt(percent.toString(), 10) >= 100 && !('status' in props) ? 'success' : status || 'normal';
    var progressInfo = void 0;
    var progress = void 0;
    var textFormatter = format || function (percentNumber) {
        return percentNumber + '%';
    };
    if (showInfo) {
        var text = void 0;
        var iconType = type === 'circle' || type === 'dashboard' ? '' : '-circle';
        if (progressStatus === 'exception') {
            text = format ? textFormatter(percent) : _react2["default"].createElement(_icon2["default"], { type: 'cross' + iconType
 });
        } else if (progressStatus === 'success') {
            text = format ? textFormatter(percent) : _react2["default"].createElement(_icon2["default"], { type: 'check' + iconType
 });
        } else {
            text = textFormatter(percent);
        }
        progressInfo = _react2["default"].createElement(
            'span',
            { className: prefixCls + '-text' },
            text
        );
    }
    if (type === 'line') {
        var percentStyle = {
            width: percent + '%',
            height: strokeWidth || 10
        };
        progress = _react2["default"].createElement(
            'div',
            null,
            _react2["default"].createElement(
                'div',
                { className: prefixCls + '-outer' },
                _react2["default"].createElement(
                    'div',
                    { className: prefixCls + '-inner' },
                    _react2["default"].createElement('div', { className: prefixCls + '-bg', style: percentStyle })
                )
            ),
            progressInfo
        );
    } else if (type === 'circle' || type === 'dashboard') {
        var circleSize = width || 132;
        var circleStyle = {
            width: circleSize,
            height: circleSize,
            fontSize: circleSize * 0.16 + 6
        };
        var circleWidth = strokeWidth || 6;
        var gapPos = gapPosition || type === 'dashboard' && 'bottom' || 'top';
        var gapDeg = gapDegree || type === 'dashboard' && 75;
        progress = _react2["default"].createElement(
            'div',
            { className: prefixCls + '-inner', style: circleStyle },
            _react2["default"].createElement(_rcProgress.Circle, { percent: percent, strokeWidth: circleWidth, trailWidth: circleWidth
, strokeColor: statusColorMap[progressStatus], trailColor: trailColor, prefixCls: prefixCls, gapDegree: gapDeg, gapPosition: gapPos
 }),
            progressInfo
        );
    }
    var classString = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-' + (type === 'dashboard' && 'circle' || type), true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-status-' +
progressStatus, true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-show-info', showInfo), _classNames), className
);
    return _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({}, restProps, { className: classString }),
        progress
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Radio"></a>[module antd.Radio](#apidoc.module.antd.Radio)

#### <a name="apidoc.element.antd.Radio.Radio"></a>[function <span class="apidocSignatureSpan">antd.</span>Radio ()](#apidoc.element.antd.Radio.Radio)
- description and source-code
```javascript
function Radio() {
    (0, _classCallCheck3["default"])(this, Radio);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio.Button"></a>[function <span class="apidocSignatureSpan">antd.Radio.</span>Button ()](#apidoc.element.antd.Radio.Button)
- description and source-code
```javascript
function RadioButton() {
    (0, _classCallCheck3["default"])(this, RadioButton);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio.Group"></a>[function <span class="apidocSignatureSpan">antd.Radio.</span>Group (props)](#apidoc.element.antd.Radio.Group)
- description and source-code
```javascript
function RadioGroup(props) {
    (0, _classCallCheck3["default"])(this, RadioGroup);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onRadioChange = function (ev) {
        var lastValue = _this.state.value;
        var value = ev.target.value;

        if (!('value' in _this.props)) {
            _this.setState({
                value: value
            });
        }
        var onChange = _this.props.onChange;
        if (onChange && value !== lastValue) {
            onChange(ev);
        }
    };
    var value = void 0;
    if ('value' in props) {
        value = props.value;
    } else if ('defaultValue' in props) {
        value = props.defaultValue;
    } else {
        var checkedValue = getCheckedValue(props.children);
        value = checkedValue && checkedValue.value;
    }
    _this.state = {
        value: value
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Radio.Button"></a>[module antd.Radio.Button](#apidoc.module.antd.Radio.Button)

#### <a name="apidoc.element.antd.Radio.Button.Button"></a>[function <span class="apidocSignatureSpan">antd.Radio.</span>Button ()](#apidoc.element.antd.Radio.Button.Button)
- description and source-code
```javascript
function RadioButton() {
    (0, _classCallCheck3["default"])(this, RadioButton);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Radio.Button.prototype"></a>[module antd.Radio.Button.prototype](#apidoc.module.antd.Radio.Button.prototype)

#### <a name="apidoc.element.antd.Radio.Button.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Radio.Button.prototype.</span>render ()](#apidoc.element.antd.Radio.Button.prototype.render)
- description and source-code
```javascript
function render() {
    var radioProps = (0, _extends3["default"])({}, this.props);
    if (this.context.radioGroup) {
        radioProps.onChange = this.context.radioGroup.onChange;
        radioProps.checked = this.props.value === this.context.radioGroup.value;
        radioProps.disabled = this.props.disabled || this.context.radioGroup.disabled;
    }
    return _react2["default"].createElement(_radio2["default"], radioProps);
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Radio.Group"></a>[module antd.Radio.Group](#apidoc.module.antd.Radio.Group)

#### <a name="apidoc.element.antd.Radio.Group.Group"></a>[function <span class="apidocSignatureSpan">antd.Radio.</span>Group (props)](#apidoc.element.antd.Radio.Group.Group)
- description and source-code
```javascript
function RadioGroup(props) {
    (0, _classCallCheck3["default"])(this, RadioGroup);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onRadioChange = function (ev) {
        var lastValue = _this.state.value;
        var value = ev.target.value;

        if (!('value' in _this.props)) {
            _this.setState({
                value: value
            });
        }
        var onChange = _this.props.onChange;
        if (onChange && value !== lastValue) {
            onChange(ev);
        }
    };
    var value = void 0;
    if ('value' in props) {
        value = props.value;
    } else if ('defaultValue' in props) {
        value = props.defaultValue;
    } else {
        var checkedValue = getCheckedValue(props.children);
        value = checkedValue && checkedValue.value;
    }
    _this.state = {
        value: value
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Radio.Group.prototype"></a>[module antd.Radio.Group.prototype](#apidoc.module.antd.Radio.Group.prototype)

#### <a name="apidoc.element.antd.Radio.Group.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Radio.Group.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('value' in nextProps) {
        this.setState({
            value: nextProps.value
        });
    } else {
        var checkedValue = getCheckedValue(nextProps.children);
        if (checkedValue) {
            this.setState({
                value: checkedValue.value
            });
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio.Group.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>getChildContext ()](#apidoc.element.antd.Radio.Group.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
    return {
        radioGroup: {
            onChange: this.onRadioChange,
            value: this.state.value,
            disabled: this.props.disabled
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Radio.Group.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>render ()](#apidoc.element.antd.Radio.Group.prototype.render)
- description and source-code
```javascript
function render() {
    var _this2 = this;

    var props = this.props;
    var _props$prefixCls = props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? 'ant-radio-group' : _props$prefixCls,
        _props$className = props.className,
        className = _props$className === undefined ? '' : _props$className;

    var classString = (0, _classnames2["default"])(prefixCls, (0, _defineProperty3["default"])({}, prefixCls + '-' + props.size,
props.size), className);
    var children = props.children;
    // 如果存在 options, 优先使用
    if (props.options && props.options.length > 0) {
        children = props.options.map(function (option, index) {
            if (typeof option === 'string') {
                return _react2["default"].createElement(
                    _radio2["default"],
                    { key: index, disabled: _this2.props.disabled, value: option, onChange: _this2.onRadioChange, checked: _this2
.state.value === option },
                    option
                );
            } else {
                return _react2["default"].createElement(
                    _radio2["default"],
                    { key: index, disabled: option.disabled || _this2.props.disabled, value: option.value, onChange: _this2.onRadioChange
, checked: _this2.state.value === option.value },
                    option.label
                );
            }
        });
    }
    return _react2["default"].createElement(
        'div',
        { className: classString, style: props.style, onMouseEnter: props.onMouseEnter, onMouseLeave: props.onMouseLeave },
        children
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Radio.Group.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">antd.Radio.Group.prototype.</span>shouldComponentUpdate (nextProps, nextState, nextContext)](#apidoc.element.antd.Radio.Group.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps, nextState, nextContext) {
    return !(0, _shallowequal2["default"])(this.props, nextProps) || !(0, _shallowequal2["default"])(this.state, nextState) || !(
0, _shallowequal2["default"])(this.context.group, nextContext.group);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Radio.contextTypes"></a>[module antd.Radio.contextTypes](#apidoc.module.antd.Radio.contextTypes)

#### <a name="apidoc.element.antd.Radio.contextTypes.radioGroup"></a>[function <span class="apidocSignatureSpan">antd.Radio.contextTypes.</span>radioGroup ()](#apidoc.element.antd.Radio.contextTypes.radioGroup)
- description and source-code
```javascript
radioGroup = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Radio.prototype"></a>[module antd.Radio.prototype](#apidoc.module.antd.Radio.prototype)

#### <a name="apidoc.element.antd.Radio.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Radio.prototype.</span>render ()](#apidoc.element.antd.Radio.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        prefixCls = _a.prefixCls,
        className = _a.className,
        children = _a.children,
        style = _a.style,
        restProps = __rest(_a, ["prefixCls", "className", "children", "style"]);
    var radioProps = (0, _extends3["default"])({}, restProps);
    if (this.context.radioGroup) {
        radioProps.onChange = this.context.radioGroup.onChange;
        radioProps.checked = this.props.value === this.context.radioGroup.value;
        radioProps.disabled = this.props.disabled || this.context.radioGroup.disabled;
    }
    var wrapperClassString = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-wrapper', true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-wrapper-checked', radioProps.checked), (0, _defineProperty3
["default"])(_classNames, prefixCls + '-wrapper-disabled', radioProps.disabled), _classNames), className);
    return _react2["default"].createElement(
        'label',
        { className: wrapperClassString, style: style, onMouseEnter: this.props.onMouseEnter, onMouseLeave: this.props.onMouseLeave
 },
        _react2["default"].createElement(_rcRadio2["default"], (0, _extends3["default"])({}, radioProps, { prefixCls: prefixCls })),
        children !== undefined ? _react2["default"].createElement(
            'span',
            null,
            children
        ) : null
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Radio.prototype.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">antd.Radio.prototype.</span>shouldComponentUpdate (nextProps, nextState, nextContext)](#apidoc.element.antd.Radio.prototype.shouldComponentUpdate)
- description and source-code
```javascript
function shouldComponentUpdate(nextProps, nextState, nextContext) {
    return !(0, _shallowequal2["default"])(this.props, nextProps) || !(0, _shallowequal2["default"])(this.state, nextState) || !(
0, _shallowequal2["default"])(this.context.radioGroup, nextContext.radioGroup);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Rate"></a>[module antd.Rate](#apidoc.module.antd.Rate)

#### <a name="apidoc.element.antd.Rate.Rate"></a>[function <span class="apidocSignatureSpan">antd.</span>Rate ()](#apidoc.element.antd.Rate.Rate)
- description and source-code
```javascript
function Rate() {
    (0, _classCallCheck3["default"])(this, Rate);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Rate.propTypes"></a>[module antd.Rate.propTypes](#apidoc.module.antd.Rate.propTypes)

#### <a name="apidoc.element.antd.Rate.propTypes.character"></a>[function <span class="apidocSignatureSpan">antd.Rate.propTypes.</span>character ()](#apidoc.element.antd.Rate.propTypes.character)
- description and source-code
```javascript
character = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Rate.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Rate.propTypes.</span>prefixCls ()](#apidoc.element.antd.Rate.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Rate.prototype"></a>[module antd.Rate.prototype](#apidoc.module.antd.Rate.prototype)

#### <a name="apidoc.element.antd.Rate.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Rate.prototype.</span>render ()](#apidoc.element.antd.Rate.prototype.render)
- description and source-code
```javascript
function render() {
    return _react2["default"].createElement(_rcRate2["default"], this.props);
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Row"></a>[module antd.Row](#apidoc.module.antd.Row)

#### <a name="apidoc.element.antd.Row.Row"></a>[function <span class="apidocSignatureSpan">antd.</span>Row ()](#apidoc.element.antd.Row.Row)
- description and source-code
```javascript
function Row() {
    (0, _classCallCheck3["default"])(this, Row);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Row.propTypes"></a>[module antd.Row.propTypes](#apidoc.module.antd.Row.propTypes)

#### <a name="apidoc.element.antd.Row.propTypes.align"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>align ()](#apidoc.element.antd.Row.propTypes.align)
- description and source-code
```javascript
align = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row.propTypes.children"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>children ()](#apidoc.element.antd.Row.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>className ()](#apidoc.element.antd.Row.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row.propTypes.gutter"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>gutter ()](#apidoc.element.antd.Row.propTypes.gutter)
- description and source-code
```javascript
gutter = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row.propTypes.justify"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>justify ()](#apidoc.element.antd.Row.propTypes.justify)
- description and source-code
```javascript
justify = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>prefixCls ()](#apidoc.element.antd.Row.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Row.propTypes.type"></a>[function <span class="apidocSignatureSpan">antd.Row.propTypes.</span>type ()](#apidoc.element.antd.Row.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Row.prototype"></a>[module antd.Row.prototype](#apidoc.module.antd.Row.prototype)

#### <a name="apidoc.element.antd.Row.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Row.prototype.</span>render ()](#apidoc.element.antd.Row.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        type = _a.type,
        justify = _a.justify,
        align = _a.align,
        className = _a.className,
        gutter = _a.gutter,
        style = _a.style,
        children = _a.children,
        _a$prefixCls = _a.prefixCls,
        prefixCls = _a$prefixCls === undefined ? 'ant-row' : _a$prefixCls,
        others = __rest(_a, ["type", "justify", "align", "className", "gutter", "style", "children", "prefixCls"]);
    var classes = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls, !type
), (0, _defineProperty3["default"])(_classNames, prefixCls + '-' + type, type), (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-' + type + '-' + justify, type && justify), (0, _defineProperty3["default"])(_classNames, prefixCls + '-' + type + '-' + align
, type && align), _classNames), className);
    var rowStyle = gutter > 0 ? (0, _objectAssign2["default"])({}, {
        marginLeft: gutter / -2,
        marginRight: gutter / -2
    }, style) : style;
    var cols = _react.Children.map(children, function (col) {
        if (!col) {
            return null;
        }
        if (col.props && gutter > 0) {
            return (0, _react.cloneElement)(col, {
                style: (0, _objectAssign2["default"])({}, {
                    paddingLeft: gutter / 2,
                    paddingRight: gutter / 2
                }, col.props.style)
            });
        }
        return col;
    });
    return _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({}, others, { className: classes, style: rowStyle }),
        cols
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Select"></a>[module antd.Select](#apidoc.module.antd.Select)

#### <a name="apidoc.element.antd.Select.Select"></a>[function <span class="apidocSignatureSpan">antd.</span>Select ()](#apidoc.element.antd.Select.Select)
- description and source-code
```javascript
function Select() {
    (0, _classCallCheck3["default"])(this, Select);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.OptGroup"></a>[function <span class="apidocSignatureSpan">antd.Select.</span>OptGroup ()](#apidoc.element.antd.Select.OptGroup)
- description and source-code
```javascript
function OptGroup() {
  (0, _classCallCheck3["default"])(this, OptGroup);
  return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.Option"></a>[function <span class="apidocSignatureSpan">antd.Select.</span>Option ()](#apidoc.element.antd.Select.Option)
- description and source-code
```javascript
function Option() {
  (0, _classCallCheck3["default"])(this, Option);
  return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Select.propTypes"></a>[module antd.Select.propTypes](#apidoc.module.antd.Select.propTypes)

#### <a name="apidoc.element.antd.Select.propTypes.choiceTransitionName"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>choiceTransitionName ()](#apidoc.element.antd.Select.propTypes.choiceTransitionName)
- description and source-code
```javascript
choiceTransitionName = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>className ()](#apidoc.element.antd.Select.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.combobox"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>combobox ()](#apidoc.element.antd.Select.propTypes.combobox)
- description and source-code
```javascript
combobox = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.notFoundContent"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>notFoundContent ()](#apidoc.element.antd.Select.propTypes.notFoundContent)
- description and source-code
```javascript
notFoundContent = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.optionLabelProp"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>optionLabelProp ()](#apidoc.element.antd.Select.propTypes.optionLabelProp)
- description and source-code
```javascript
optionLabelProp = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>prefixCls ()](#apidoc.element.antd.Select.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.showSearch"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>showSearch ()](#apidoc.element.antd.Select.propTypes.showSearch)
- description and source-code
```javascript
showSearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.size"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>size ()](#apidoc.element.antd.Select.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.propTypes.transitionName"></a>[function <span class="apidocSignatureSpan">antd.Select.propTypes.</span>transitionName ()](#apidoc.element.antd.Select.propTypes.transitionName)
- description and source-code
```javascript
transitionName = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Select.prototype"></a>[module antd.Select.prototype](#apidoc.module.antd.Select.prototype)

#### <a name="apidoc.element.antd.Select.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.Select.prototype.</span>getLocale ()](#apidoc.element.antd.Select.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var antLocale = this.context.antLocale;

    if (antLocale && antLocale.Select) {
        return antLocale.Select;
    }
    return {
        notFoundContent: 'Not Found'
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Select.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Select.prototype.</span>render ()](#apidoc.element.antd.Select.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        prefixCls = _a.prefixCls,
        _a$className = _a.className,
        className = _a$className === undefined ? '' : _a$className,
        size = _a.size,
        mode = _a.mode,
        multiple = _a.multiple,
        tags = _a.tags,
        combobox = _a.combobox,
        restProps = __rest(_a, ["prefixCls", "className", "size", "mode", "multiple", "tags", "combobox"]);
    (0, _warning2["default"])(!multiple && !tags && !combobox, ''Select[multiple|tags|combobox]' is deprecated, please use 'Select
[mode]' instead.');
    var cls = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls + '-lg', size
 === 'large'), (0, _defineProperty3["default"])(_classNames, prefixCls + '-sm', size === 'small'), _classNames), className);
    var locale = this.getLocale();
    var _props = this.props,
        _props$notFoundConten = _props.notFoundContent,
        notFoundContent = _props$notFoundConten === undefined ? locale.notFoundContent : _props$notFoundConten,
        optionLabelProp = _props.optionLabelProp;

    var isCombobox = mode === 'combobox' || combobox;
    if (isCombobox) {
        notFoundContent = null;
        // children 带 dom 结构时，无法填入输入框
        optionLabelProp = optionLabelProp || 'value';
    }
    var modeConfig = {
        multiple: mode === 'multiple' || multiple,
        tags: mode === 'tags' || tags,
        combobox: isCombobox
    };
    return _react2["default"].createElement(_rcSelect2["default"], (0, _extends3["default"])({}, restProps, modeConfig, { prefixCls
: prefixCls, className: cls, optionLabelProp: optionLabelProp || 'children', notFoundContent: notFoundContent }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Slider"></a>[module antd.Slider](#apidoc.module.antd.Slider)

#### <a name="apidoc.element.antd.Slider.Slider"></a>[function <span class="apidocSignatureSpan">antd.</span>Slider (props)](#apidoc.element.antd.Slider.Slider)
- description and source-code
```javascript
function Slider(props) {
    (0, _classCallCheck3["default"])(this, Slider);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.toggleTooltipVisible = function (index, visible) {
        _this.setState(function (_ref) {
            var visibles = _ref.visibles;
            return {
                visibles: (0, _extends4["default"])({}, visibles, (0, _defineProperty3["default"])({}, index, visible))
            };
        });
    };
    _this.handleWithTooltip = function (_a) {
        var value = _a.value,
            dragging = _a.dragging,
            index = _a.index,
            restProps = __rest(_a, ["value", "dragging", "index"]);

        var _this$props = _this.props,
            tooltipPrefixCls = _this$props.tooltipPrefixCls,
            tipFormatter = _this$props.tipFormatter;
        var visibles = _this.state.visibles;

        return _react2["default"].createElement(
            _tooltip2["default"],
            { prefixCls: tooltipPrefixCls, title: tipFormatter ? tipFormatter(value) : '', visible: tipFormatter && (visibles[index
] || dragging), placement: 'top', transitionName: 'zoom-down', key: index },
            _react2["default"].createElement(_Handle2["default"], (0, _extends4["default"])({}, restProps, { onMouseEnter: function
 onMouseEnter() {
                    return _this.toggleTooltipVisible(index, true);
                }, onMouseLeave: function onMouseLeave() {
                    return _this.toggleTooltipVisible(index, false);
                } }))
        );
    };
    _this.state = {
        visibles: {}
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Slider.defaultProps"></a>[module antd.Slider.defaultProps](#apidoc.module.antd.Slider.defaultProps)

#### <a name="apidoc.element.antd.Slider.defaultProps.tipFormatter"></a>[function <span class="apidocSignatureSpan">antd.Slider.defaultProps.</span>tipFormatter (value)](#apidoc.element.antd.Slider.defaultProps.tipFormatter)
- description and source-code
```javascript
function tipFormatter(value) {
    return value.toString();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Slider.prototype"></a>[module antd.Slider.prototype](#apidoc.module.antd.Slider.prototype)

#### <a name="apidoc.element.antd.Slider.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Slider.prototype.</span>render ()](#apidoc.element.antd.Slider.prototype.render)
- description and source-code
```javascript
function render() {
    var _a = this.props,
        range = _a.range,
        restProps = __rest(_a, ["range"]);
    if (range) {
        return _react2["default"].createElement(_Range2["default"], (0, _extends4["default"])({}, restProps, { handle: this.handleWithTooltip
 }));
    }
    return _react2["default"].createElement(_Slider2["default"], (0, _extends4["default"])({}, restProps, { handle: this.handleWithTooltip
 }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Spin"></a>[module antd.Spin](#apidoc.module.antd.Spin)

#### <a name="apidoc.element.antd.Spin.Spin"></a>[function <span class="apidocSignatureSpan">antd.</span>Spin (props)](#apidoc.element.antd.Spin.Spin)
- description and source-code
```javascript
function Spin(props) {
    (0, _classCallCheck3["default"])(this, Spin);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    var spinning = props.spinning;
    _this.state = {
        spinning: spinning
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Spin.propTypes"></a>[module antd.Spin.propTypes](#apidoc.module.antd.Spin.propTypes)

#### <a name="apidoc.element.antd.Spin.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>className ()](#apidoc.element.antd.Spin.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>prefixCls ()](#apidoc.element.antd.Spin.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.propTypes.size"></a>[function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>size ()](#apidoc.element.antd.Spin.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.propTypes.spinning"></a>[function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>spinning ()](#apidoc.element.antd.Spin.propTypes.spinning)
- description and source-code
```javascript
spinning = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.propTypes.wrapperClassName"></a>[function <span class="apidocSignatureSpan">antd.Spin.propTypes.</span>wrapperClassName ()](#apidoc.element.antd.Spin.propTypes.wrapperClassName)
- description and source-code
```javascript
wrapperClassName = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Spin.prototype"></a>[module antd.Spin.prototype](#apidoc.module.antd.Spin.prototype)

#### <a name="apidoc.element.antd.Spin.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>componentDidMount ()](#apidoc.element.antd.Spin.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    if (!(0, _isCssAnimationSupported2["default"])()) {
        // Show text in IE8/9
        (0, _reactDom.findDOMNode)(this).className += ' ' + this.props.prefixCls + '-show-text';
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Spin.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    var _this2 = this;

    var currentSpinning = this.props.spinning;
    var spinning = nextProps.spinning;
    var delay = this.props.delay;

    if (this.debounceTimeout) {
        clearTimeout(this.debounceTimeout);
    }
    if (currentSpinning && !spinning) {
        this.debounceTimeout = setTimeout(function () {
            return _this2.setState({ spinning: spinning });
        }, 300);
        if (this.delayTimeout) {
            clearTimeout(this.delayTimeout);
        }
    } else {
        if (spinning && delay && !isNaN(Number(delay))) {
            this.delayTimeout = setTimeout(function () {
                return _this2.setState({ spinning: spinning });
            }, delay);
        } else {
            this.setState({ spinning: spinning });
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Spin.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    if (this.debounceTimeout) {
        clearTimeout(this.debounceTimeout);
    }
    if (this.delayTimeout) {
        clearTimeout(this.delayTimeout);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.prototype.isNestedPattern"></a>[function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>isNestedPattern ()](#apidoc.element.antd.Spin.prototype.isNestedPattern)
- description and source-code
```javascript
function isNestedPattern() {
    return !!(this.props && this.props.children);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Spin.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Spin.prototype.</span>render ()](#apidoc.element.antd.Spin.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        className = _a.className,
        size = _a.size,
        prefixCls = _a.prefixCls,
        tip = _a.tip,
        wrapperClassName = _a.wrapperClassName,
        restProps = __rest(_a, ["className", "size", "prefixCls", "tip", "wrapperClassName"]);var spinning = this.state.spinning
;

    var spinClassName = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames,
prefixCls + '-sm', size === 'small'), (0, _defineProperty3["default"])(_classNames, prefixCls + '-lg', size === 'large'), (0, _defineProperty3
["default"])(_classNames, prefixCls + '-spinning', spinning), (0, _defineProperty3["default"])(_classNames, prefixCls + '-show-text
', !!tip), _classNames), className);
    // fix https://fb.me/react-unknown-prop
    var divProps = (0, _omit2["default"])(restProps, ['spinning', 'delay']);
    var spinElement = _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({}, divProps, { className: spinClassName }),
        _react2["default"].createElement(
            'span',
            { className: prefixCls + '-dot' },
            _react2["default"].createElement('i', null),
            _react2["default"].createElement('i', null),
            _react2["default"].createElement('i', null),
            _react2["default"].createElement('i', null)
        ),
        tip ? _react2["default"].createElement(
            'div',
            { className: prefixCls + '-text' },
            tip
        ) : null
    );
    if (this.isNestedPattern()) {
        var _classNames2;

        var animateClassName = prefixCls + '-nested-loading';
        if (wrapperClassName) {
            animateClassName += ' ' + wrapperClassName;
        }
        var containerClassName = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2,
prefixCls + '-container', true), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-blur', spinning), _classNames2));
        return _react2["default"].createElement(
            _rcAnimate2["default"],
            (0, _extends3["default"])({}, divProps, { component: 'div', className: animateClassName, style: null, transitionName
: 'fade' }),
            spinning && _react2["default"].createElement(
                'div',
                { key: 'loading' },
                spinElement
            ),
            _react2["default"].createElement(
                'div',
                { className: containerClassName, key: 'container' },
                this.props.children
            )
        );
    }
    return spinElement;
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Steps"></a>[module antd.Steps](#apidoc.module.antd.Steps)

#### <a name="apidoc.element.antd.Steps.Steps"></a>[function <span class="apidocSignatureSpan">antd.</span>Steps ()](#apidoc.element.antd.Steps.Steps)
- description and source-code
```javascript
function Steps() {
    (0, _classCallCheck3["default"])(this, Steps);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Steps.Step"></a>[function <span class="apidocSignatureSpan">antd.Steps.</span>Step ()](#apidoc.element.antd.Steps.Step)
- description and source-code
```javascript
function Step() {
  _classCallCheck(this, Step);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Steps.Step"></a>[module antd.Steps.Step](#apidoc.module.antd.Steps.Step)

#### <a name="apidoc.element.antd.Steps.Step.Step"></a>[function <span class="apidocSignatureSpan">antd.Steps.</span>Step ()](#apidoc.element.antd.Steps.Step.Step)
- description and source-code
```javascript
function Step() {
  _classCallCheck(this, Step);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Steps.Step.prototype"></a>[module antd.Steps.Step.prototype](#apidoc.module.antd.Steps.Step.prototype)

#### <a name="apidoc.element.antd.Steps.Step.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Steps.Step.prototype.</span>render ()](#apidoc.element.antd.Steps.Step.prototype.render)
- description and source-code
```javascript
function render() {
  var _classNames, _classNames2;

  var _props = this.props;
  var className = _props.className;
  var prefixCls = _props.prefixCls;
  var style = _props.style;
  var itemWidth = _props.itemWidth;
  var _props$status = _props.status;
  var status = _props$status === undefined ? 'wait' : _props$status;
  var iconPrefix = _props.iconPrefix;
  var icon = _props.icon;
  var wrapperStyle = _props.wrapperStyle;
  var adjustMarginRight = _props.adjustMarginRight;
  var stepLast = _props.stepLast;
  var stepNumber = _props.stepNumber;
  var description = _props.description;
  var title = _props.title;
  var progressDot = _props.progressDot;

  var restProps = _objectWithoutProperties(_props, ['className', 'prefixCls', 'style', 'itemWidth', 'status', 'iconPrefix', 'icon
', 'wrapperStyle', 'adjustMarginRight', 'stepLast', 'stepNumber', 'description', 'title', 'progressDot']);

  var iconClassName = (0, _classnames2["default"])((_classNames = {}, _defineProperty(_classNames, prefixCls + '-icon', true), _defineProperty
(_classNames, iconPrefix + 'icon', true), _defineProperty(_classNames, iconPrefix + 'icon-' + icon, icon && isString(icon)), _defineProperty
(_classNames, iconPrefix + 'icon-check', !icon && status === 'finish'), _defineProperty(_classNames, iconPrefix + 'icon-cross', !
icon && status === 'error'), _classNames));

  var iconNode = void 0;
  var iconDot = _react2["default"].createElement('span', { className: prefixCls + '-icon-dot' });
  // 'progressDot' enjoy the highest priority
  if (!!progressDot) {
    if (typeof progressDot === 'function') {
      iconNode = _react2["default"].createElement(
        'span',
        { className: prefixCls + '-icon' },
        progressDot(iconDot, { index: stepNumber - 1, status: status, title: title, description: description })
      );
    } else {
      iconNode = _react2["default"].createElement(
        'span',
        { className: prefixCls + '-icon' },
        iconDot
      );
    }
  } else if (icon && !isString(icon)) {
    iconNode = _react2["default"].createElement(
      'span',
      { className: prefixCls + '-icon' },
      icon
    );
  } else if (icon || status === 'finish' || status === 'error') {
    iconNode = _react2["default"].createElement('span', { className: iconClassName });
  } else {
    iconNode = _react2["default"].createElement(
      'span',
      { className: prefixCls + '-icon' },
      stepNumber
    );
  }
  var classString = (0, _classnames2["default"])((_classNames2 = {}, _defineProperty(_classNames2, prefixCls + '-item', true), _defineProperty
(_classNames2, prefixCls + '-item-last', stepLast), _defineProperty(_classNames2, prefixCls + '-status-' + status, true), _defineProperty
(_classNames2, prefixCls + '-custom', icon), _defineProperty(_classNames2, className, !!className), _classNames2));
  return _react2["default"].createElement(
    'div',
    _extends({}, restProps, {
      className: classString,
      style: _extends({ width: itemWidth, marginRight: adjustMarginRight }, style)
    }),
    stepLast ? '' : _react2["default"].createElement(
      'div',
      {
        ref: 'tail',
        className: prefixCls + '-tail',
        style: { paddingRight: -adjustMarginRight }
      },
      _react2["default"].createElement('i', null)
    ),
    _react2["default"].createElement(
      'div',
      { className: prefixCls + '-step' },
      _react2["default"].createElement(
        'div',
        {
          className: prefixCls + '-head',
          style: { background: wrapperStyle.background || wrapperStyle.backgroundColor }
        },
        _react2["default"].createElement(
          'div',
          { className: prefixCls + '-head-inner' },
          iconNode
        )
      ),
      _react2["default"].createElement(
        'div',
        { ref: 'main', className: prefixCls + '-main' },
        _react2["default"].createElement(
          'div',
          {
            className: prefixCls + '-title',
            style: { background: wrapperStyle.background || wrapperStyle.backgroundColor }
          },
          title ...
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Steps.propTypes"></a>[module antd.Steps.propTypes](#apidoc.module.antd.Steps.propTypes)

#### <a name="apidoc.element.antd.Steps.propTypes.current"></a>[function <span class="apidocSignatureSpan">antd.Steps.propTypes.</span>current ()](#apidoc.element.antd.Steps.propTypes.current)
- description and source-code
```javascript
current = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Steps.propTypes.iconPrefix"></a>[function <span class="apidocSignatureSpan">antd.Steps.propTypes.</span>iconPrefix ()](#apidoc.element.antd.Steps.propTypes.iconPrefix)
- description and source-code
```javascript
iconPrefix = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Steps.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Steps.propTypes.</span>prefixCls ()](#apidoc.element.antd.Steps.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Steps.prototype"></a>[module antd.Steps.prototype](#apidoc.module.antd.Steps.prototype)

#### <a name="apidoc.element.antd.Steps.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Steps.prototype.</span>render ()](#apidoc.element.antd.Steps.prototype.render)
- description and source-code
```javascript
function render() {
    return _react2["default"].createElement(_rcSteps2["default"], this.props);
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Switch"></a>[module antd.Switch](#apidoc.module.antd.Switch)

#### <a name="apidoc.element.antd.Switch.Switch"></a>[function <span class="apidocSignatureSpan">antd.</span>Switch ()](#apidoc.element.antd.Switch.Switch)
- description and source-code
```javascript
function Switch() {
    (0, _classCallCheck3["default"])(this, Switch);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Switch.propTypes"></a>[module antd.Switch.propTypes](#apidoc.module.antd.Switch.propTypes)

#### <a name="apidoc.element.antd.Switch.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Switch.propTypes.</span>className ()](#apidoc.element.antd.Switch.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Switch.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Switch.propTypes.</span>prefixCls ()](#apidoc.element.antd.Switch.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Switch.propTypes.size"></a>[function <span class="apidocSignatureSpan">antd.Switch.propTypes.</span>size ()](#apidoc.element.antd.Switch.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Switch.prototype"></a>[module antd.Switch.prototype](#apidoc.module.antd.Switch.prototype)

#### <a name="apidoc.element.antd.Switch.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Switch.prototype.</span>render ()](#apidoc.element.antd.Switch.prototype.render)
- description and source-code
```javascript
function render() {
    var _props = this.props,
        prefixCls = _props.prefixCls,
        size = _props.size,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className;

    var classes = (0, _classnames2["default"])(className, (0, _defineProperty3["default"])({}, prefixCls + '-small', size === 'small
'));
    return _react2["default"].createElement(_rcSwitch2["default"], (0, _extends3["default"])({}, this.props, { className: classes
 }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Table"></a>[module antd.Table](#apidoc.module.antd.Table)

#### <a name="apidoc.element.antd.Table.Table"></a>[function <span class="apidocSignatureSpan">antd.</span>Table (props)](#apidoc.element.antd.Table.Table)
- description and source-code
```javascript
function Table(props) {
    (0, _classCallCheck3["default"])(this, Table);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.getCheckboxPropsByItem = function (item, index) {
        var _this$props$rowSelect = _this.props.rowSelection,
            rowSelection = _this$props$rowSelect === undefined ? {} : _this$props$rowSelect;

        if (!rowSelection.getCheckboxProps) {
            return {};
        }
        var key = _this.getRecordKey(item, index);
        // Cache checkboxProps
        if (!_this.CheckboxPropsCache[key]) {
            _this.CheckboxPropsCache[key] = rowSelection.getCheckboxProps(item);
        }
        return _this.CheckboxPropsCache[key];
    };
    _this.handleFilter = function (column, nextFilters) {
        var props = _this.props;
        var pagination = (0, _objectAssign2["default"])({}, _this.state.pagination);
        var filters = (0, _objectAssign2["default"])({}, _this.state.filters, (0, _defineProperty3["default"])({}, _this.getColumnKey
(column), nextFilters));
        // Remove filters not in current columns
        var currentColumnKeys = [];
        (0, _util.treeMap)(_this.columns, function (c) {
            if (!c.children) {
                currentColumnKeys.push(_this.getColumnKey(c));
            }
        });
        Object.keys(filters).forEach(function (columnKey) {
            if (currentColumnKeys.indexOf(columnKey) < 0) {
                delete filters[columnKey];
            }
        });
        if (props.pagination) {
            // Reset current prop
            pagination.current = 1;
            pagination.onChange(pagination.current);
        }
        var newState = {
            pagination: pagination,
            filters: {}
        };
        var filtersToSetState = (0, _objectAssign2["default"])({}, filters);
        // Remove filters which is controlled
        _this.getFilteredValueColumns().forEach(function (col) {
            var columnKey = _this.getColumnKey(col);
            if (columnKey) {
                delete filtersToSetState[columnKey];
            }
        });
        if (Object.keys(filtersToSetState).length > 0) {
            newState.filters = filtersToSetState;
        }
        // Controlled current prop will not respond user interaction
        if ((0, _typeof3["default"])(props.pagination) === 'object' && 'current' in props.pagination) {
            newState.pagination = (0, _objectAssign2["default"])({}, pagination, {
                current: _this.state.pagination.current
            });
        }
        _this.setState(newState, function () {
            _this.store.setState({
                selectionDirty: false
            });
            var onChange = _this.props.onChange;
            if (onChange) {
                onChange.apply(null, _this.prepareParamsArguments((0, _objectAssign2["default"])({}, _this.state, {
                    selectionDirty: false,
                    filters: filters,
                    pagination: pagination
                })));
            }
        });
    };
    _this.handleSelect = function (record, rowIndex, e) {
        var checked = e.target.checked;
        var defaultSelection = _this.store.getState().selectionDirty ? [] : _this.getDefaultSelection();
        var selectedRowKeys = _this.store.getState().selectedRowKeys.concat(defaultSelection);
        var key = _this.getRecordKey(record, rowIndex);
        if (checked) {
            selectedRowKeys.push(_this.getRecordKey(record, rowIndex));
        } else {
            selectedRowKeys = selectedRowKeys.filter(function (i) {
                return key !== i;
            });
        }
        _this.store.setState({
            selectionDirty: true
        });
        _this.setSelectedRowKeys(selectedRowKeys, {
            selectWay: 'onSelect',
            record: record,
            checked: checked
        });
    };
    _this.handleRadioSelect = function (record, rowIndex, e) {
        var checked = e.target.checked;
        var defaultSelection = _this.store.getState(). ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.Column"></a>[function <span class="apidocSignatureSpan">antd.Table.</span>Column ()](#apidoc.element.antd.Table.Column)
- description and source-code
```javascript
function Column() {
  (0, _classCallCheck3["default"])(this, Column);
  return (0, _possibleConstructorReturn3["default"])(this, _RcTable$Column.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.ColumnGroup"></a>[function <span class="apidocSignatureSpan">antd.Table.</span>ColumnGroup ()](#apidoc.element.antd.Table.ColumnGroup)
- description and source-code
```javascript
function ColumnGroup() {
  (0, _classCallCheck3["default"])(this, ColumnGroup);
  return (0, _possibleConstructorReturn3["default"])(this, _RcTable$ColumnGroup.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Table.contextTypes"></a>[module antd.Table.contextTypes](#apidoc.module.antd.Table.contextTypes)

#### <a name="apidoc.element.antd.Table.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Table.contextTypes.</span>antLocale ()](#apidoc.element.antd.Table.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Table.propTypes"></a>[module antd.Table.propTypes](#apidoc.module.antd.Table.propTypes)

#### <a name="apidoc.element.antd.Table.propTypes.bordered"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>bordered ()](#apidoc.element.antd.Table.propTypes.bordered)
- description and source-code
```javascript
bordered = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>className ()](#apidoc.element.antd.Table.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.columns"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>columns ()](#apidoc.element.antd.Table.propTypes.columns)
- description and source-code
```javascript
columns = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.dataSource"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>dataSource ()](#apidoc.element.antd.Table.propTypes.dataSource)
- description and source-code
```javascript
dataSource = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.dropdownPrefixCls"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>dropdownPrefixCls ()](#apidoc.element.antd.Table.propTypes.dropdownPrefixCls)
- description and source-code
```javascript
dropdownPrefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.loading"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>loading ()](#apidoc.element.antd.Table.propTypes.loading)
- description and source-code
```javascript
loading = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.locale"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>locale ()](#apidoc.element.antd.Table.propTypes.locale)
- description and source-code
```javascript
locale = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.onChange"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>onChange ()](#apidoc.element.antd.Table.propTypes.onChange)
- description and source-code
```javascript
onChange = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>prefixCls ()](#apidoc.element.antd.Table.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.rowSelection"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>rowSelection ()](#apidoc.element.antd.Table.propTypes.rowSelection)
- description and source-code
```javascript
rowSelection = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.size"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>size ()](#apidoc.element.antd.Table.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.propTypes.useFixedHeader"></a>[function <span class="apidocSignatureSpan">antd.Table.propTypes.</span>useFixedHeader ()](#apidoc.element.antd.Table.propTypes.useFixedHeader)
- description and source-code
```javascript
useFixedHeader = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Table.prototype"></a>[module antd.Table.prototype](#apidoc.module.antd.Table.prototype)

#### <a name="apidoc.element.antd.Table.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Table.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    this.columns = nextProps.columns || (0, _util.normalizeColumns)(nextProps.children);
    if ('pagination' in nextProps || 'pagination' in this.props) {
        this.setState(function (previousState) {
            var newPagination = (0, _objectAssign2["default"])({}, defaultPagination, previousState.pagination, nextProps.pagination
);
            newPagination.current = newPagination.current || 1;
            newPagination.pageSize = newPagination.pageSize || 10;
            return { pagination: nextProps.pagination !== false ? newPagination : emptyObject };
        });
    }
    if (nextProps.rowSelection && 'selectedRowKeys' in nextProps.rowSelection) {
        this.store.setState({
            selectedRowKeys: nextProps.rowSelection.selectedRowKeys || []
        });
        var rowSelection = this.props.rowSelection;

        if (rowSelection && nextProps.rowSelection.getCheckboxProps !== rowSelection.getCheckboxProps) {
            this.CheckboxPropsCache = {};
        }
    }
    if ('dataSource' in nextProps && nextProps.dataSource !== this.props.dataSource) {
        this.store.setState({
            selectionDirty: false
        });
        this.CheckboxPropsCache = {};
    }
    if (this.getSortOrderColumns(this.columns).length > 0) {
        var sortState = this.getSortStateFromColumns(this.columns);
        if (sortState.sortColumn !== this.state.sortColumn || sortState.sortOrder !== this.state.sortOrder) {
            this.setState(sortState);
        }
    }
    var filteredValueColumns = this.getFilteredValueColumns(this.columns);
    if (filteredValueColumns.length > 0) {
        var filtersFromColumns = this.getFiltersFromColumns(this.columns);
        var newFilters = (0, _objectAssign2["default"])({}, this.state.filters);
        Object.keys(filtersFromColumns).forEach(function (key) {
            newFilters[key] = filtersFromColumns[key];
        });
        if (this.isFiltersChanged(newFilters)) {
            this.setState({ filters: newFilters });
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.findColumn"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>findColumn (myKey)](#apidoc.element.antd.Table.prototype.findColumn)
- description and source-code
```javascript
function findColumn(myKey) {
    var _this8 = this;

    var column = void 0;
    (0, _util.treeMap)(this.columns, function (c) {
        if (_this8.getColumnKey(c) === myKey) {
            column = c;
        }
    });
    return column;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getColumnKey"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getColumnKey (column, index)](#apidoc.element.antd.Table.prototype.getColumnKey)
- description and source-code
```javascript
function getColumnKey(column, index) {
    return column.key || column.dataIndex || index;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getCurrentPageData"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getCurrentPageData ()](#apidoc.element.antd.Table.prototype.getCurrentPageData)
- description and source-code
```javascript
function getCurrentPageData() {
    var data = this.getLocalData();
    var current = void 0;
    var pageSize = void 0;
    var state = this.state;
    // 如果没有分页的话，默认全部展示
    if (!this.hasPagination()) {
        pageSize = Number.MAX_VALUE;
        current = 1;
    } else {
        pageSize = state.pagination.pageSize;
        current = this.getMaxCurrent(state.pagination.total || data.length);
    }
    // 分页
    // ---
    // 当数据量少于等于每页数量时，直接设置数据
    // 否则进行读取分页数据
    if (data.length > pageSize || pageSize === Number.MAX_VALUE) {
        data = data.filter(function (_, i) {
            return i >= (current - 1) * pageSize && i < current * pageSize;
        });
    }
    return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getDefaultPagination"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getDefaultPagination (props)](#apidoc.element.antd.Table.prototype.getDefaultPagination)
- description and source-code
```javascript
function getDefaultPagination(props) {
    var pagination = props.pagination || {};
    return this.hasPagination(props) ? (0, _objectAssign2["default"])({}, defaultPagination, pagination, {
        current: pagination.defaultCurrent || pagination.current || 1,
        pageSize: pagination.defaultPageSize || pagination.pageSize || 10
    }) : {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getDefaultSelection"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getDefaultSelection ()](#apidoc.element.antd.Table.prototype.getDefaultSelection)
- description and source-code
```javascript
function getDefaultSelection() {
    var _this2 = this;

    var _props$rowSelection = this.props.rowSelection,
        rowSelection = _props$rowSelection === undefined ? {} : _props$rowSelection;

    if (!rowSelection.getCheckboxProps) {
        return [];
    }
    return this.getFlatData().filter(function (item, rowIndex) {
        return _this2.getCheckboxPropsByItem(item, rowIndex).defaultChecked;
    }).map(function (record, rowIndex) {
        return _this2.getRecordKey(record, rowIndex);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getFilteredValueColumns"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFilteredValueColumns (columns)](#apidoc.element.antd.Table.prototype.getFilteredValueColumns)
- description and source-code
```javascript
function getFilteredValueColumns(columns) {
    return (0, _util.flatFilter)(columns || this.columns || [], function (column) {
        return typeof column.filteredValue !== 'undefined';
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getFiltersFromColumns"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFiltersFromColumns (columns)](#apidoc.element.antd.Table.prototype.getFiltersFromColumns)
- description and source-code
```javascript
function getFiltersFromColumns(columns) {
    var _this5 = this;

    var filters = {};
    this.getFilteredValueColumns(columns).forEach(function (col) {
        filters[_this5.getColumnKey(col)] = col.filteredValue;
    });
    return filters;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getFlatCurrentPageData"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFlatCurrentPageData ()](#apidoc.element.antd.Table.prototype.getFlatCurrentPageData)
- description and source-code
```javascript
function getFlatCurrentPageData() {
    return (0, _util.flatArray)(this.getCurrentPageData());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getFlatData"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getFlatData ()](#apidoc.element.antd.Table.prototype.getFlatData)
- description and source-code
```javascript
function getFlatData() {
    return (0, _util.flatArray)(this.getLocalData());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getLocalData"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getLocalData ()](#apidoc.element.antd.Table.prototype.getLocalData)
- description and source-code
```javascript
function getLocalData() {
    var _this10 = this;

    var state = this.state;
    var dataSource = this.props.dataSource;

    var data = dataSource || [];
    // 优化本地排序
    data = data.slice(0);
    var sorterFn = this.getSorterFn();
    if (sorterFn) {
        data = this.recursiveSort(data, sorterFn);
    }
    // 筛选
    if (state.filters) {
        Object.keys(state.filters).forEach(function (columnKey) {
            var col = _this10.findColumn(columnKey);
            if (!col) {
                return;
            }
            var values = state.filters[columnKey] || [];
            if (values.length === 0) {
                return;
            }
            var onFilter = col.onFilter;
            data = onFilter ? data.filter(function (record) {
                return values.some(function (v) {
                    return onFilter(v, record);
                });
            }) : data;
        });
    }
    return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getLocale ()](#apidoc.element.antd.Table.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var locale = {};
    if (this.context.antLocale && this.context.antLocale.Table) {
        locale = this.context.antLocale.Table;
    }
    return (0, _objectAssign2["default"])({}, defaultLocale, locale, this.props.locale);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getMaxCurrent"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getMaxCurrent (total)](#apidoc.element.antd.Table.prototype.getMaxCurrent)
- description and source-code
```javascript
function getMaxCurrent(total) {
    var _state$pagination = this.state.pagination,
        current = _state$pagination.current,
        pageSize = _state$pagination.pageSize;

    if ((current - 1) * pageSize >= total) {
        return Math.floor((total - 1) / pageSize) + 1;
    }
    return current;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getSortOrderColumns"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getSortOrderColumns (columns)](#apidoc.element.antd.Table.prototype.getSortOrderColumns)
- description and source-code
```javascript
function getSortOrderColumns(columns) {
    return (0, _util.flatFilter)(columns || this.columns || [], function (column) {
        return 'sortOrder' in column;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getSortStateFromColumns"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getSortStateFromColumns (columns)](#apidoc.element.antd.Table.prototype.getSortStateFromColumns)
- description and source-code
```javascript
function getSortStateFromColumns(columns) {
    // return fisrt column which sortOrder is not falsy
    var sortedColumn = this.getSortOrderColumns(columns).filter(function (col) {
        return col.sortOrder;
    })[0];
    if (sortedColumn) {
        return {
            sortColumn: sortedColumn,
            sortOrder: sortedColumn.sortOrder
        };
    }
    return {
        sortColumn: null,
        sortOrder: null
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.getSorterFn"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>getSorterFn ()](#apidoc.element.antd.Table.prototype.getSorterFn)
- description and source-code
```javascript
function getSorterFn() {
    var _state = this.state,
        sortOrder = _state.sortOrder,
        sortColumn = _state.sortColumn;

    if (!sortOrder || !sortColumn || typeof sortColumn.sorter !== 'function') {
        return;
    }
    return function (a, b) {
        var result = sortColumn.sorter(a, b);
        if (result !== 0) {
            return sortOrder === 'descend' ? -result : result;
        }
        return 0;
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.hasPagination"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>hasPagination (props)](#apidoc.element.antd.Table.prototype.hasPagination)
- description and source-code
```javascript
function hasPagination(props) {
    return (props || this.props).pagination !== false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.isFiltersChanged"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>isFiltersChanged (filters)](#apidoc.element.antd.Table.prototype.isFiltersChanged)
- description and source-code
```javascript
function isFiltersChanged(filters) {
    var _this4 = this;

    var filtersChanged = false;
    if (Object.keys(filters).length !== Object.keys(this.state.filters).length) {
        filtersChanged = true;
    } else {
        Object.keys(filters).forEach(function (columnKey) {
            if (filters[columnKey] !== _this4.state.filters[columnKey]) {
                filtersChanged = true;
            }
        });
    }
    return filtersChanged;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.isSortColumn"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>isSortColumn (column)](#apidoc.element.antd.Table.prototype.isSortColumn)
- description and source-code
```javascript
function isSortColumn(column) {
    var sortColumn = this.state.sortColumn;

    if (!column || !sortColumn) {
        return false;
    }
    return this.getColumnKey(sortColumn) === this.getColumnKey(column);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.prepareParamsArguments"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>prepareParamsArguments (state)](#apidoc.element.antd.Table.prototype.prepareParamsArguments)
- description and source-code
```javascript
function prepareParamsArguments(state) {
    var pagination = (0, _extends3["default"])({}, state.pagination);
    // remove useless handle function in Table.onChange
    delete pagination.onChange;
    delete pagination.onShowSizeChange;
    var filters = state.filters;
    var sorter = {};
    if (state.sortColumn && state.sortOrder) {
        sorter.column = state.sortColumn;
        sorter.order = state.sortOrder;
        sorter.field = state.sortColumn.dataIndex;
        sorter.columnKey = this.getColumnKey(state.sortColumn);
    }
    return [pagination, filters, sorter];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.recursiveSort"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>recursiveSort (data, sorterFn)](#apidoc.element.antd.Table.prototype.recursiveSort)
- description and source-code
```javascript
function recursiveSort(data, sorterFn) {
    var _this9 = this;

    var _props$childrenColumn = this.props.childrenColumnName,
        childrenColumnName = _props$childrenColumn === undefined ? 'children' : _props$childrenColumn;

    return data.sort(sorterFn).map(function (item) {
        return item[childrenColumnName] ? (0, _objectAssign2["default"])({}, item, (0, _defineProperty3["default"])({}, childrenColumnName
, _this9.recursiveSort(item[childrenColumnName], sorterFn))) : item;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>render ()](#apidoc.element.antd.Table.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames2,
        _this11 = this;

    var _a = this.props,
        style = _a.style,
        className = _a.className,
        prefixCls = _a.prefixCls,
        showHeader = _a.showHeader,
        restProps = __rest(_a, ["style", "className", "prefixCls", "showHeader"]);
    var data = this.getCurrentPageData();
    var columns = this.renderRowSelection();
    var expandIconAsCell = this.props.expandedRowRender && this.props.expandIconAsCell !== false;
    var locale = this.getLocale();
    var classString = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2, prefixCls + '-' +
this.props.size, true), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-bordered', this.props.bordered), (0, _defineProperty3
["default"])(_classNames2, prefixCls + '-empty', !data.length), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-without
-column-header', !showHeader), _classNames2));
    columns = this.renderColumnsDropdown(columns);
    columns = columns.map(function (column, i) {
        var newColumn = (0, _objectAssign2["default"])({}, column);
        newColumn.key = _this11.getColumnKey(newColumn, i);
        return newColumn;
    });
    var expandIconColumnIndex = columns[0] && columns[0].key === 'selection-column' ? 1 : 0;
    if ('expandIconColumnIndex' in restProps) {
        expandIconColumnIndex = restProps.expandIconColumnIndex;
    }
    var table = _react2["default"].createElement(_rcTable2["default"], (0, _extends3["default"])({ key: 'table' }, restProps, {
prefixCls: prefixCls, data: data, columns: columns, showHeader: showHeader, className: classString, expandIconColumnIndex: expandIconColumnIndex
, expandIconAsCell: expandIconAsCell, emptyText: function emptyText() {
            return locale.emptyText;
        } }));
    // if there is no pagination or no data,
    // the height of spin should decrease by half of pagination
    var paginationPatchClass = this.hasPagination() && data && data.length !== 0 ? prefixCls + '-with-pagination' : prefixCls + '-
without-pagination';
    var loading = this.props.loading;
    if (typeof loading === 'boolean') {
        loading = {
            spinning: loading
        };
    }
    return _react2["default"].createElement(
        'div',
        { className: (0, _classnames2["default"])(prefixCls + '-wrapper', className), style: style },
        _react2["default"].createElement(
            _spin2["default"],
            (0, _extends3["default"])({}, loading, { className: loading ? paginationPatchClass + ' ' + prefixCls + '-spin-holder
' : '' }),
            table,
            this.renderPagination()
        )
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Table.prototype.renderColumnsDropdown"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>renderColumnsDropdown (columns)](#apidoc.element.antd.Table.prototype.renderColumnsDropdown)
- description and source-code
```javascript
function renderColumnsDropdown(columns) {
    var _this7 = this;

    var _props2 = this.props,
        prefixCls = _props2.prefixCls,
        dropdownPrefixCls = _props2.dropdownPrefixCls;
    var sortOrder = this.state.sortOrder;

    var locale = this.getLocale();
    return (0, _util.treeMap)(columns, function (originColumn, i) {
        var column = (0, _objectAssign2["default"])({}, originColumn);
        var key = _this7.getColumnKey(column, i);
        var filterDropdown = void 0;
        var sortButton = void 0;
        if (column.filters && column.filters.length > 0 || column.filterDropdown) {
            var colFilters = _this7.state.filters[key] || [];
            filterDropdown = _react2["default"].createElement(_filterDropdown2["default"], { locale: locale, column: column, selectedKeys
: colFilters, confirmFilter: _this7.handleFilter, prefixCls: prefixCls + '-filter', dropdownPrefixCls: dropdownPrefixCls || 'ant
-dropdown' });
        }
        if (column.sorter) {
            var isSortColumn = _this7.isSortColumn(column);
            if (isSortColumn) {
                column.className = column.className || '';
                if (sortOrder) {
                    column.className += ' ' + prefixCls + '-column-sort';
                }
            }
            var isAscend = isSortColumn && sortOrder === 'ascend';
            var isDescend = isSortColumn && sortOrder === 'descend';
            sortButton = _react2["default"].createElement(
                'div',
                { className: prefixCls + '-column-sorter' },
                _react2["default"].createElement(
                    'span',
                    { className: prefixCls + '-column-sorter-up ' + (isAscend ? 'on' : 'off'), title: '\u2191', onClick: function
 onClick() {
                            return _this7.toggleSortOrder('ascend', column);
                        } },
                    _react2["default"].createElement(_icon2["default"], { type: 'caret-up' })
                ),
                _react2["default"].createElement(
                    'span',
                    { className: prefixCls + '-column-sorter-down ' + (isDescend ? 'on' : 'off'), title: '\u2193', onClick: function
 onClick() {
                            return _this7.toggleSortOrder('descend', column);
                        } },
                    _react2["default"].createElement(_icon2["default"], { type: 'caret-down' })
                )
            );
        }
        column.title = _react2["default"].createElement(
            'span',
            null,
            column.title,
            sortButton,
            filterDropdown
        );
        return column;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.renderPagination"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>renderPagination ()](#apidoc.element.antd.Table.prototype.renderPagination)
- description and source-code
```javascript
function renderPagination() {
    // 强制不需要分页
    if (!this.hasPagination()) {
        return null;
    }
    var size = 'default';
    var pagination = this.state.pagination;

    if (pagination.size) {
        size = pagination.size;
    } else if (this.props.size === 'middle' || this.props.size === 'small') {
        size = 'small';
    }
    var total = pagination.total || this.getLocalData().length;
    return total > 0 ? _react2["default"].createElement(_pagination2["default"], (0, _extends3["default"])({ key: 'pagination' },
pagination, { className: this.props.prefixCls + '-pagination', onChange: this.handlePageChange, total: total, size: size, current
: this.getMaxCurrent(total), onShowSizeChange: this.handleShowSizeChange })) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.renderRowSelection"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>renderRowSelection ()](#apidoc.element.antd.Table.prototype.renderRowSelection)
- description and source-code
```javascript
function renderRowSelection() {
    var _this6 = this;

    var _props = this.props,
        prefixCls = _props.prefixCls,
        rowSelection = _props.rowSelection;

    var columns = this.columns.concat();
    if (rowSelection) {
        var data = this.getFlatCurrentPageData().filter(function (item, index) {
            if (rowSelection.getCheckboxProps) {
                return !_this6.getCheckboxPropsByItem(item, index).disabled;
            }
            return true;
        });
        var selectionColumnClass = (0, _classnames2["default"])(prefixCls + '-selection-column', (0, _defineProperty3["default"])({},
prefixCls + '-selection-column-custom', rowSelection.selections));
        var selectionColumn = {
            key: 'selection-column',
            render: this.renderSelectionBox(rowSelection.type),
            className: selectionColumnClass
        };
        if (rowSelection.type !== 'radio') {
            var checkboxAllDisabled = data.every(function (item, index) {
                return _this6.getCheckboxPropsByItem(item, index).disabled;
            });
            selectionColumn.title = _react2["default"].createElement(_SelectionCheckboxAll2["default"], { store: this.store, locale
: this.getLocale(), data: data, getCheckboxPropsByItem: this.getCheckboxPropsByItem, getRecordKey: this.getRecordKey, disabled:
checkboxAllDisabled, prefixCls: prefixCls, onSelect: this.handleSelectRow, selections: rowSelection.selections });
        }
        if (columns.some(function (column) {
            return column.fixed === 'left' || column.fixed === true;
        })) {
            selectionColumn.fixed = 'left';
        }
        if (columns[0] && columns[0].key === 'selection-column') {
            columns[0] = selectionColumn;
        } else {
            columns.unshift(selectionColumn);
        }
    }
    return columns;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.setSelectedRowKeys"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>setSelectedRowKeys (selectedRowKeys, _ref)](#apidoc.element.antd.Table.prototype.setSelectedRowKeys)
- description and source-code
```javascript
function setSelectedRowKeys(selectedRowKeys, _ref) {
    var _this3 = this;

    var selectWay = _ref.selectWay,
        record = _ref.record,
        checked = _ref.checked,
        changeRowKeys = _ref.changeRowKeys;
    var _props$rowSelection2 = this.props.rowSelection,
        rowSelection = _props$rowSelection2 === undefined ? {} : _props$rowSelection2;

    if (rowSelection && !('selectedRowKeys' in rowSelection)) {
        this.store.setState({ selectedRowKeys: selectedRowKeys });
    }
    var data = this.getFlatData();
    if (!rowSelection.onChange && !rowSelection[selectWay]) {
        return;
    }
    var selectedRows = data.filter(function (row, i) {
        return selectedRowKeys.indexOf(_this3.getRecordKey(row, i)) >= 0;
    });
    if (rowSelection.onChange) {
        rowSelection.onChange(selectedRowKeys, selectedRows);
    }
    if (selectWay === 'onSelect' && rowSelection.onSelect) {
        rowSelection.onSelect(record, checked, selectedRows);
    } else if (selectWay === 'onSelectAll' && rowSelection.onSelectAll) {
        var changeRows = data.filter(function (row, i) {
            return changeRowKeys.indexOf(_this3.getRecordKey(row, i)) >= 0;
        });
        rowSelection.onSelectAll(checked, selectedRows, changeRows);
    } else if (selectWay === 'onSelectInvert' && rowSelection.onSelectInvert) {
        rowSelection.onSelectInvert(selectedRowKeys);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Table.prototype.toggleSortOrder"></a>[function <span class="apidocSignatureSpan">antd.Table.prototype.</span>toggleSortOrder (order, column)](#apidoc.element.antd.Table.prototype.toggleSortOrder)
- description and source-code
```javascript
function toggleSortOrder(order, column) {
    var _state2 = this.state,
        sortColumn = _state2.sortColumn,
        sortOrder = _state2.sortOrder;
    // 只同时允许一列进行排序，否则会导致排序顺序的逻辑问题

    var isSortColumn = this.isSortColumn(column);
    if (!isSortColumn) {
        sortOrder = order;
        sortColumn = column;
    } else {
        if (sortOrder === order) {
            sortOrder = '';
            sortColumn = null;
        } else {
            sortOrder = order;
        }
    }
    var newState = {
        sortOrder: sortOrder,
        sortColumn: sortColumn
    };
    // Controlled
    if (this.getSortOrderColumns().length === 0) {
        this.setState(newState);
    }
    var onChange = this.props.onChange;
    if (onChange) {
        onChange.apply(null, this.prepareParamsArguments((0, _objectAssign2["default"])({}, this.state, newState)));
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tabs"></a>[module antd.Tabs](#apidoc.module.antd.Tabs)

#### <a name="apidoc.element.antd.Tabs.Tabs"></a>[function <span class="apidocSignatureSpan">antd.</span>Tabs ()](#apidoc.element.antd.Tabs.Tabs)
- description and source-code
```javascript
function Tabs() {
    (0, _classCallCheck3["default"])(this, Tabs);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.createNewTab = function (targetKey) {
        var onEdit = _this.props.onEdit;
        if (onEdit) {
            onEdit(targetKey, 'add');
        }
    };
    _this.removeTab = function (targetKey, e) {
        e.stopPropagation();
        if (!targetKey) {
            return;
        }
        var onEdit = _this.props.onEdit;
        if (onEdit) {
            onEdit(targetKey, 'remove');
        }
    };
    _this.handleChange = function (activeKey) {
        var onChange = _this.props.onChange;
        if (onChange) {
            onChange(activeKey);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs.TabPane"></a>[function <span class="apidocSignatureSpan">antd.Tabs.</span>TabPane (props, context, updater)](#apidoc.element.antd.Tabs.TabPane)
- description and source-code
```javascript
TabPane = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tabs.TabPane"></a>[module antd.Tabs.TabPane](#apidoc.module.antd.Tabs.TabPane)

#### <a name="apidoc.element.antd.Tabs.TabPane.TabPane"></a>[function <span class="apidocSignatureSpan">antd.Tabs.</span>TabPane (props, context, updater)](#apidoc.element.antd.Tabs.TabPane.TabPane)
- description and source-code
```javascript
TabPane = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs.TabPane.getDefaultProps"></a>[function <span class="apidocSignatureSpan">antd.Tabs.TabPane.</span>getDefaultProps ()](#apidoc.element.antd.Tabs.TabPane.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return { placeholder: null };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tabs.TabPane.prototype"></a>[module antd.Tabs.TabPane.prototype](#apidoc.module.antd.Tabs.TabPane.prototype)

#### <a name="apidoc.element.antd.Tabs.TabPane.prototype.constructor"></a>[function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>constructor (props, context, updater)](#apidoc.element.antd.Tabs.TabPane.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs.TabPane.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>getDOMNode ()](#apidoc.element.antd.Tabs.TabPane.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs.TabPane.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.</span>render ()](#apidoc.element.antd.Tabs.TabPane.prototype.render)
- description and source-code
```javascript
function render() {
  var _classnames;

  var props = this.props;
  var className = props.className,
      destroyInactiveTabPane = props.destroyInactiveTabPane,
      active = props.active,
      forceRender = props.forceRender;

  this._isActived = this._isActived || active;
  var prefixCls = props.rootPrefixCls + '-tabpane';
  var cls = (0, _classnames3["default"])((_classnames = {}, (0, _defineProperty3["default"])(_classnames, prefixCls, 1), (0, _defineProperty3
["default"])(_classnames, prefixCls + '-inactive', !active), (0, _defineProperty3["default"])(_classnames, prefixCls + '-active',
active), (0, _defineProperty3["default"])(_classnames, className, className), _classnames));
  var isRender = destroyInactiveTabPane ? active : this._isActived;
  return _react2["default"].createElement(
    'div',
    {
      style: props.style,
      role: 'tabpanel',
      'aria-hidden': props.active ? 'false' : 'true',
      className: cls
    },
    isRender || forceRender ? props.children : props.placeholder
  );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Tabs.TabPane.prototype.__reactAutoBindMap"></a>[module antd.Tabs.TabPane.prototype.__reactAutoBindMap](#apidoc.module.antd.Tabs.TabPane.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.antd.Tabs.TabPane.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">antd.Tabs.TabPane.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.antd.Tabs.TabPane.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tabs.prototype"></a>[module antd.Tabs.prototype](#apidoc.module.antd.Tabs.prototype)

#### <a name="apidoc.element.antd.Tabs.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Tabs.prototype.</span>componentDidMount ()](#apidoc.element.antd.Tabs.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
    var NO_FLEX = ' no-flex';
    var tabNode = (0, _reactDom.findDOMNode)(this);
    if (tabNode && !(0, _isFlexSupported2["default"])() && tabNode.className.indexOf(NO_FLEX) === -1) {
        tabNode.className += NO_FLEX;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tabs.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tabs.prototype.</span>render ()](#apidoc.element.antd.Tabs.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames,
        _this2 = this;

    var _props = this.props,
        prefixCls = _props.prefixCls,
        _props$className = _props.className,
        className = _props$className === undefined ? '' : _props$className,
        size = _props.size,
        _props$type = _props.type,
        type = _props$type === undefined ? 'line' : _props$type,
        tabPosition = _props.tabPosition,
        children = _props.children,
        tabBarExtraContent = _props.tabBarExtraContent,
        tabBarStyle = _props.tabBarStyle,
        hideAdd = _props.hideAdd,
        onTabClick = _props.onTabClick,
        onPrevClick = _props.onPrevClick,
        onNextClick = _props.onNextClick,
        animated = _props.animated;

    var _ref = (typeof animated === 'undefined' ? 'undefined' : (0, _typeof3["default"])(animated)) === 'object' ? {
        inkBarAnimated: animated.inkBar, tabPaneAnimated: animated.tabPane
    } : {
        inkBarAnimated: animated, tabPaneAnimated: animated
    },
        inkBarAnimated = _ref.inkBarAnimated,
        tabPaneAnimated = _ref.tabPaneAnimated;

    (0, _warning2["default"])(!(type.indexOf('card') >= 0 && size === 'small'), 'Tabs[type=card|editable-card] doesn\'t have small
 size, it\'s by designed.');
    var cls = (0, _classnames2["default"])(className, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-mini', size === 'small' || size === 'mini'), (0, _defineProperty3["default"])(_classNames, prefixCls + '-vertical', tabPosition
 === 'left' || tabPosition === 'right'), (0, _defineProperty3["default"])(_classNames, prefixCls + '-card', type.indexOf('card') >=
0), (0, _defineProperty3["default"])(_classNames, prefixCls + '-' + type, true), (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-no-animation', !animated), _classNames));
    // only card type tabs can be added and closed
    var childrenWithClose = void 0;
    if (type === 'editable-card') {
        childrenWithClose = [];
        _react2["default"].Children.forEach(children, function (child, index) {
            var closable = child.props.closable;
            closable = typeof closable === 'undefined' ? true : closable;
            var closeIcon = closable ? _react2["default"].createElement(_icon2["default"], { type: 'close', onClick: function onClick
(e) {
                    return _this2.removeTab(child.key, e);
                } }) : null;
            childrenWithClose.push((0, _react.cloneElement)(child, {
                tab: _react2["default"].createElement(
                    'div',
                    { className: closable ? undefined : prefixCls + '-tab-unclosable' },
                    child.props.tab,
                    closeIcon
                ),
                key: child.key || index
            }));
        });
        // Add new tab handler
        if (!hideAdd) {
            tabBarExtraContent = _react2["default"].createElement(
                'span',
                null,
                _react2["default"].createElement(_icon2["default"], { type: 'plus', className: prefixCls + '-new-tab', onClick:
this.createNewTab }),
                tabBarExtraContent
            );
        }
    }
    tabBarExtraContent = tabBarExtraContent ? _react2["default"].createElement(
        'div',
        { className: prefixCls + '-extra-content' },
        tabBarExtraContent
    ) : null;
    var renderTabBar = function renderTabBar() {
        return _react2["default"].createElement(_ScrollableInkTabBar2["default"], { inkBarAnimated: inkBarAnimated, extraContent
: tabBarExtraContent, onTabClick: onTabClick, onPrevClick: onPrevClick, onNextClick: onNextClick, style: tabBarStyle });
    };
    return _react2["default"].createElement(
        _rcTabs2["default"],
        (0, _extends3["default"])({}, this.props, { className: cls, tabBarPosition: tabPosition, renderTabBar: renderTabBar, renderTabContent
: function renderTabContent() {
                return _react2["default"].createElement(_TabContent2["default"], { animated: tabPaneAnimated, animatedWithMargin
: t ...
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Tag"></a>[module antd.Tag](#apidoc.module.antd.Tag)

#### <a name="apidoc.element.antd.Tag.Tag"></a>[function <span class="apidocSignatureSpan">antd.</span>Tag (props)](#apidoc.element.antd.Tag.Tag)
- description and source-code
```javascript
function Tag(props) {
    (0, _classCallCheck3["default"])(this, Tag);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.close = function (e) {
        var onClose = _this.props.onClose;
        if (onClose) {
            onClose(e);
        }
        if (e.defaultPrevented) {
            return;
        }
        var dom = _reactDom2["default"].findDOMNode(_this);
        dom.style.width = dom.getBoundingClientRect().width + 'px';
        // It's Magic Code, don't know why
        dom.style.width = dom.getBoundingClientRect().width + 'px';
        _this.setState({
            closing: true
        });
    };
    _this.animationEnd = function (_, existed) {
        if (!existed && !_this.state.closed) {
            _this.setState({
                closed: true,
                closing: false
            });
            var afterClose = _this.props.afterClose;
            if (afterClose) {
                afterClose();
            }
        }
    };
    _this.state = {
        closing: false,
        closed: false
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tag.CheckableTag"></a>[function <span class="apidocSignatureSpan">antd.Tag.</span>CheckableTag ()](#apidoc.element.antd.Tag.CheckableTag)
- description and source-code
```javascript
function CheckableTag() {
    (0, _classCallCheck3["default"])(this, CheckableTag);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.handleClick = function () {
        var _this$props = _this.props,
            checked = _this$props.checked,
            onChange = _this$props.onChange;

        if (onChange) {
            onChange(!checked);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tag.CheckableTag"></a>[module antd.Tag.CheckableTag](#apidoc.module.antd.Tag.CheckableTag)

#### <a name="apidoc.element.antd.Tag.CheckableTag.CheckableTag"></a>[function <span class="apidocSignatureSpan">antd.Tag.</span>CheckableTag ()](#apidoc.element.antd.Tag.CheckableTag.CheckableTag)
- description and source-code
```javascript
function CheckableTag() {
    (0, _classCallCheck3["default"])(this, CheckableTag);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));

    _this.handleClick = function () {
        var _this$props = _this.props,
            checked = _this$props.checked,
            onChange = _this$props.onChange;

        if (onChange) {
            onChange(!checked);
        }
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tag.CheckableTag.prototype"></a>[module antd.Tag.CheckableTag.prototype](#apidoc.module.antd.Tag.CheckableTag.prototype)

#### <a name="apidoc.element.antd.Tag.CheckableTag.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tag.CheckableTag.prototype.</span>render ()](#apidoc.element.antd.Tag.CheckableTag.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        _a$prefixCls = _a.prefixCls,
        prefixCls = _a$prefixCls === undefined ? 'ant-tag' : _a$prefixCls,
        className = _a.className,
        checked = _a.checked,
        restProps = __rest(_a, ["prefixCls", "className", "checked"]);
    var cls = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-checkable', true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-checkable-checked', checked), _classNames),
className);
    delete restProps.onChange; // TypeScript cannot check delete now.
    return _react2["default"].createElement('div', (0, _extends3["default"])({}, restProps, { className: cls, onClick: this.handleClick
 }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Tag.prototype"></a>[module antd.Tag.prototype](#apidoc.module.antd.Tag.prototype)

#### <a name="apidoc.element.antd.Tag.prototype.isPresetColor"></a>[function <span class="apidocSignatureSpan">antd.Tag.prototype.</span>isPresetColor (color)](#apidoc.element.antd.Tag.prototype.isPresetColor)
- description and source-code
```javascript
function isPresetColor(color) {
    return (/^(pink|red|yellow|orange|cyan|green|blue|purple)(-inverse)?$/.test(color)
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tag.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tag.prototype.</span>render ()](#apidoc.element.antd.Tag.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames;

    var _a = this.props,
        prefixCls = _a.prefixCls,
        closable = _a.closable,
        color = _a.color,
        className = _a.className,
        children = _a.children,
        style = _a.style,
        otherProps = __rest(_a, ["prefixCls", "closable", "color", "className", "children", "style"]);
    var closeIcon = closable ? _react2["default"].createElement(_icon2["default"], { type: 'cross', onClick: this.close }) : '';
    var isPresetColor = this.isPresetColor(color);
    var classString = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-' + color, isPresetColor), (0, _defineProperty3["default"])(_classNames, prefixCls + '-has-color', color && !isPresetColor), (
0, _defineProperty3["default"])(_classNames, prefixCls + '-close', this.state.closing), _classNames), className);
    // fix https://fb.me/react-unknown-prop
    var divProps = (0, _omit2["default"])(otherProps, ['onClose', 'afterClose']);
    var tagStyle = (0, _objectAssign2["default"])({
        backgroundColor: color && !isPresetColor ? color : null
    }, style);
    var tag = this.state.closed ? null : _react2["default"].createElement(
        'div',
        (0, _extends3["default"])({ 'data-show': !this.state.closing }, divProps, { className: classString, style: tagStyle }),
        _react2["default"].createElement(
            'span',
            { className: prefixCls + '-text' },
            children
        ),
        closeIcon
    );
    return _react2["default"].createElement(
        _rcAnimate2["default"],
        { component: '', showProp: 'data-show', transitionName: prefixCls + '-zoom', transitionAppear: true, onEnd: this.animationEnd
 },
        tag
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.TimePicker"></a>[module antd.TimePicker](#apidoc.module.antd.TimePicker)

#### <a name="apidoc.element.antd.TimePicker.TimePicker"></a>[function <span class="apidocSignatureSpan">antd.</span>TimePicker ()](#apidoc.element.antd.TimePicker.TimePicker)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.TimePicker.contextTypes"></a>[module antd.TimePicker.contextTypes](#apidoc.module.antd.TimePicker.contextTypes)

#### <a name="apidoc.element.antd.TimePicker.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.TimePicker.contextTypes.</span>antLocale ()](#apidoc.element.antd.TimePicker.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.TimePicker.prototype"></a>[module antd.TimePicker.prototype](#apidoc.module.antd.TimePicker.prototype)

#### <a name="apidoc.element.antd.TimePicker.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.TimePicker.prototype.</span>getLocale ()](#apidoc.element.antd.TimePicker.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var antLocale = this.context.antLocale;

    var localeFromContext = antLocale && antLocale[componentName];
    var localeFromProps = this.props.locale || {};
    return (0, _extends3["default"])({}, defaultLocale, localeFromContext || {}, localeFromProps);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Timeline"></a>[module antd.Timeline](#apidoc.module.antd.Timeline)

#### <a name="apidoc.element.antd.Timeline.Timeline"></a>[function <span class="apidocSignatureSpan">antd.</span>Timeline ()](#apidoc.element.antd.Timeline.Timeline)
- description and source-code
```javascript
function Timeline() {
    (0, _classCallCheck3["default"])(this, Timeline);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Timeline.Item"></a>[function <span class="apidocSignatureSpan">antd.Timeline.</span>Item ()](#apidoc.element.antd.Timeline.Item)
- description and source-code
```javascript
function TimelineItem() {
    (0, _classCallCheck3["default"])(this, TimelineItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Timeline.Item"></a>[module antd.Timeline.Item](#apidoc.module.antd.Timeline.Item)

#### <a name="apidoc.element.antd.Timeline.Item.Item"></a>[function <span class="apidocSignatureSpan">antd.Timeline.</span>Item ()](#apidoc.element.antd.Timeline.Item.Item)
- description and source-code
```javascript
function TimelineItem() {
    (0, _classCallCheck3["default"])(this, TimelineItem);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Timeline.Item.prototype"></a>[module antd.Timeline.Item.prototype](#apidoc.module.antd.Timeline.Item.prototype)

#### <a name="apidoc.element.antd.Timeline.Item.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Timeline.Item.prototype.</span>render ()](#apidoc.element.antd.Timeline.Item.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames, _classNames2;

    var _a = this.props,
        prefixCls = _a.prefixCls,
        className = _a.className,
        _a$color = _a.color,
        color = _a$color === undefined ? '' : _a$color,
        last = _a.last,
        children = _a.children,
        pending = _a.pending,
        dot = _a.dot,
        restProps = __rest(_a, ["prefixCls", "className", "color", "last", "children", "pending", "dot"]);
    var itemClassName = (0, _classnames2["default"])((_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls + '-
item', true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-item-last', last), (0, _defineProperty3["default"])(_classNames
, prefixCls + '-item-pending', pending), _classNames), className);
    var dotClassName = (0, _classnames2["default"])((_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2, prefixCls
 + '-item-head', true), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-item-head-custom', dot), (0, _defineProperty3
["default"])(_classNames2, prefixCls + '-item-head-' + color, true), _classNames2));
    return _react2["default"].createElement(
        'li',
        (0, _extends3["default"])({}, restProps, { className: itemClassName }),
        _react2["default"].createElement('div', { className: prefixCls + '-item-tail' }),
        _react2["default"].createElement(
            'div',
            { className: dotClassName, style: { borderColor: /blue|red|green/.test(color) ? null : color } },
            dot
        ),
        _react2["default"].createElement(
            'div',
            { className: prefixCls + '-item-content' },
            children
        )
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Timeline.prototype"></a>[module antd.Timeline.prototype](#apidoc.module.antd.Timeline.prototype)

#### <a name="apidoc.element.antd.Timeline.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Timeline.prototype.</span>render ()](#apidoc.element.antd.Timeline.prototype.render)
- description and source-code
```javascript
function render() {
    var _a = this.props,
        prefixCls = _a.prefixCls,
        children = _a.children,
        pending = _a.pending,
        className = _a.className,
        restProps = __rest(_a, ["prefixCls", "children", "pending", "className"]);
    var pendingNode = typeof pending === 'boolean' ? null : pending;
    var classString = (0, _classnames2["default"])(prefixCls, (0, _defineProperty3["default"])({}, prefixCls + '-pending', !!pending
), className);
    var items = _react2["default"].Children.map(children, function (ele, idx) {
        return _react2["default"].cloneElement(ele, {
            last: idx === children.length - 1
        });
    });
    var pendingItem = !!pending ? _react2["default"].createElement(
        _TimelineItem2["default"],
        { pending: !!pending },
        pendingNode
    ) : null;
    return _react2["default"].createElement(
        'ul',
        (0, _extends3["default"])({}, restProps, { className: classString }),
        items,
        pendingItem
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Tooltip"></a>[module antd.Tooltip](#apidoc.module.antd.Tooltip)

#### <a name="apidoc.element.antd.Tooltip.Tooltip"></a>[function <span class="apidocSignatureSpan">antd.</span>Tooltip (props)](#apidoc.element.antd.Tooltip.Tooltip)
- description and source-code
```javascript
function Tooltip(props) {
    (0, _classCallCheck3["default"])(this, Tooltip);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onVisibleChange = function (visible) {
        var onVisibleChange = _this.props.onVisibleChange;

        if (!('visible' in _this.props)) {
            _this.setState({ visible: _this.isNoTitle() ? false : visible });
        }
        if (onVisibleChange && !_this.isNoTitle()) {
            onVisibleChange(visible);
        }
    };
    // 动态设置动画点
    _this.onPopupAlign = function (domNode, align) {
        var placements = _this.getPlacements();
        // 当前返回的位置
        var placement = Object.keys(placements).filter(function (key) {
            return placements[key].points[0] === align.points[0] && placements[key].points[1] === align.points[1];
        })[0];
        if (!placement) {
            return;
        }
        // 根据当前坐标设置动画点
        var rect = domNode.getBoundingClientRect();
        var transformOrigin = {
            top: '50%',
            left: '50%'
        };
        if (placement.indexOf('top') >= 0 || placement.indexOf('Bottom') >= 0) {
            transformOrigin.top = rect.height - align.offset[1] + 'px';
        } else if (placement.indexOf('Top') >= 0 || placement.indexOf('bottom') >= 0) {
            transformOrigin.top = -align.offset[1] + 'px';
        }
        if (placement.indexOf('left') >= 0 || placement.indexOf('Right') >= 0) {
            transformOrigin.left = rect.width - align.offset[0] + 'px';
        } else if (placement.indexOf('right') >= 0 || placement.indexOf('Left') >= 0) {
            transformOrigin.left = -align.offset[0] + 'px';
        }
        domNode.style.transformOrigin = transformOrigin.left + ' ' + transformOrigin.top;
    };
    _this.state = {
        visible: !!props.visible
    };
    return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tooltip.prototype"></a>[module antd.Tooltip.prototype](#apidoc.module.antd.Tooltip.prototype)

#### <a name="apidoc.element.antd.Tooltip.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Tooltip.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('visible' in nextProps) {
        this.setState({ visible: nextProps.visible });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip.prototype.getDisabledCompatibleChildren"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>getDisabledCompatibleChildren (element)](#apidoc.element.antd.Tooltip.prototype.getDisabledCompatibleChildren)
- description and source-code
```javascript
function getDisabledCompatibleChildren(element) {
    if ((element.type.__ANT_BUTTON || element.type === 'button') && element.props.disabled && this.isHoverTrigger()) {
        // Pick some layout related style properties up to span
        // Prevent layout bugs like https://github.com/ant-design/ant-design/issues/5254
        var _splitObject = splitObject(element.props.style, ['position', 'left', 'right', 'top', 'bottom', 'float', 'display', '
zIndex']),
            picked = _splitObject.picked,
            omited = _splitObject.omited;

        var spanStyle = (0, _extends3["default"])({ display: 'inline-block' }, picked, { cursor: 'not-allowed' });
        var buttonStyle = (0, _extends3["default"])({}, omited, { pointerEvents: 'none' });
        var child = (0, _react.cloneElement)(element, {
            style: buttonStyle,
            className: null
        });
        return _react2["default"].createElement(
            'span',
            { style: spanStyle, className: element.props.className },
            child
        );
    }
    return element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip.prototype.getPlacements"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>getPlacements ()](#apidoc.element.antd.Tooltip.prototype.getPlacements)
- description and source-code
```javascript
function getPlacements() {
    var _props = this.props,
        builtinPlacements = _props.builtinPlacements,
        arrowPointAtCenter = _props.arrowPointAtCenter;

    return builtinPlacements || (0, _placements2["default"])({
        arrowPointAtCenter: arrowPointAtCenter,
        verticalArrowShift: 8
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip.prototype.getPopupDomNode"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>getPopupDomNode ()](#apidoc.element.antd.Tooltip.prototype.getPopupDomNode)
- description and source-code
```javascript
function getPopupDomNode() {
    return this.refs.tooltip.getPopupDomNode();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip.prototype.isHoverTrigger"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>isHoverTrigger ()](#apidoc.element.antd.Tooltip.prototype.isHoverTrigger)
- description and source-code
```javascript
function isHoverTrigger() {
    var trigger = this.props.trigger;

    if (!trigger || trigger === 'hover') {
        return true;
    }
    if (Array.isArray(trigger)) {
        return trigger.indexOf('hover') >= 0;
    }
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip.prototype.isNoTitle"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>isNoTitle ()](#apidoc.element.antd.Tooltip.prototype.isNoTitle)
- description and source-code
```javascript
function isNoTitle() {
    var _props2 = this.props,
        title = _props2.title,
        overlay = _props2.overlay;

    return !title && !overlay; // overlay for old version compatibility
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tooltip.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tooltip.prototype.</span>render ()](#apidoc.element.antd.Tooltip.prototype.render)
- description and source-code
```javascript
function render() {
    var props = this.props,
        state = this.state;
    var prefixCls = props.prefixCls,
        title = props.title,
        overlay = props.overlay,
        openClassName = props.openClassName,
        getPopupContainer = props.getPopupContainer,
        getTooltipContainer = props.getTooltipContainer;

    var children = props.children;
    var visible = state.visible;
    // Hide tooltip when there is no title
    if (!('visible' in props) && this.isNoTitle()) {
        visible = false;
    }
    var child = this.getDisabledCompatibleChildren(_react2["default"].isValidElement(children) ? children : _react2["default"].createElement
(
        'span',
        null,
        children
    ));
    var childProps = child.props;
    var childCls = (0, _classnames2["default"])(childProps.className, (0, _defineProperty3["default"])({}, openClassName || prefixCls
 + '-open', true));
    return _react2["default"].createElement(
        _rcTooltip2["default"],
        (0, _extends3["default"])({}, this.props, { getTooltipContainer: getPopupContainer || getTooltipContainer, ref: 'tooltip
', builtinPlacements: this.getPlacements(), overlay: overlay || title, visible: visible, onVisibleChange: this.onVisibleChange,
onPopupAlign: this.onPopupAlign }),
        visible ? (0, _react.cloneElement)(child, { className: childCls }) : child
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Transfer"></a>[module antd.Transfer](#apidoc.module.antd.Transfer)

#### <a name="apidoc.element.antd.Transfer.Transfer"></a>[function <span class="apidocSignatureSpan">antd.</span>Transfer ()](#apidoc.element.antd.Transfer.Transfer)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Transfer.contextTypes"></a>[module antd.Transfer.contextTypes](#apidoc.module.antd.Transfer.contextTypes)

#### <a name="apidoc.element.antd.Transfer.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Transfer.contextTypes.</span>antLocale ()](#apidoc.element.antd.Transfer.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Transfer.defaultProps"></a>[module antd.Transfer.defaultProps](#apidoc.module.antd.Transfer.defaultProps)

#### <a name="apidoc.element.antd.Transfer.defaultProps.render"></a>[function <span class="apidocSignatureSpan">antd.Transfer.defaultProps.</span>render ()](#apidoc.element.antd.Transfer.defaultProps.render)
- description and source-code
```javascript
function noop() {}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Transfer.propTypes"></a>[module antd.Transfer.propTypes](#apidoc.module.antd.Transfer.propTypes)

#### <a name="apidoc.element.antd.Transfer.propTypes.body"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>body ()](#apidoc.element.antd.Transfer.propTypes.body)
- description and source-code
```javascript
body = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.className"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>className ()](#apidoc.element.antd.Transfer.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.dataSource"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>dataSource ()](#apidoc.element.antd.Transfer.propTypes.dataSource)
- description and source-code
```javascript
dataSource = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.filterOption"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>filterOption ()](#apidoc.element.antd.Transfer.propTypes.filterOption)
- description and source-code
```javascript
filterOption = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.footer"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>footer ()](#apidoc.element.antd.Transfer.propTypes.footer)
- description and source-code
```javascript
footer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.height"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>height ()](#apidoc.element.antd.Transfer.propTypes.height)
- description and source-code
```javascript
height = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.lazy"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>lazy ()](#apidoc.element.antd.Transfer.propTypes.lazy)
- description and source-code
```javascript
lazy = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.listStyle"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>listStyle ()](#apidoc.element.antd.Transfer.propTypes.listStyle)
- description and source-code
```javascript
listStyle = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.notFoundContent"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>notFoundContent ()](#apidoc.element.antd.Transfer.propTypes.notFoundContent)
- description and source-code
```javascript
notFoundContent = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.onChange"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>onChange ()](#apidoc.element.antd.Transfer.propTypes.onChange)
- description and source-code
```javascript
onChange = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.operations"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>operations ()](#apidoc.element.antd.Transfer.propTypes.operations)
- description and source-code
```javascript
operations = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.prefixCls"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>prefixCls ()](#apidoc.element.antd.Transfer.propTypes.prefixCls)
- description and source-code
```javascript
prefixCls = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.render"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>render ()](#apidoc.element.antd.Transfer.propTypes.render)
- description and source-code
```javascript
render = function () { [native code] }
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Transfer.propTypes.rowKey"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>rowKey ()](#apidoc.element.antd.Transfer.propTypes.rowKey)
- description and source-code
```javascript
rowKey = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.searchPlaceholder"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>searchPlaceholder ()](#apidoc.element.antd.Transfer.propTypes.searchPlaceholder)
- description and source-code
```javascript
searchPlaceholder = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.showSearch"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>showSearch ()](#apidoc.element.antd.Transfer.propTypes.showSearch)
- description and source-code
```javascript
showSearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.targetKeys"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>targetKeys ()](#apidoc.element.antd.Transfer.propTypes.targetKeys)
- description and source-code
```javascript
targetKeys = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Transfer.propTypes.titles"></a>[function <span class="apidocSignatureSpan">antd.Transfer.propTypes.</span>titles ()](#apidoc.element.antd.Transfer.propTypes.titles)
- description and source-code
```javascript
titles = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Transfer.prototype"></a>[module antd.Transfer.prototype](#apidoc.module.antd.Transfer.prototype)

#### <a name="apidoc.element.antd.Transfer.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.Transfer.prototype.</span>getLocale ()](#apidoc.element.antd.Transfer.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var antLocale = this.context.antLocale;

    var localeFromContext = antLocale && antLocale[componentName];
    var localeFromProps = this.props.locale || {};
    return (0, _extends3["default"])({}, defaultLocale, localeFromContext || {}, localeFromProps);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tree"></a>[module antd.Tree](#apidoc.module.antd.Tree)

#### <a name="apidoc.element.antd.Tree.Tree"></a>[function <span class="apidocSignatureSpan">antd.</span>Tree ()](#apidoc.element.antd.Tree.Tree)
- description and source-code
```javascript
function Tree() {
    (0, _classCallCheck3["default"])(this, Tree);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component2.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode"></a>[function <span class="apidocSignatureSpan">antd.Tree.</span>TreeNode (props)](#apidoc.element.antd.Tree.TreeNode)
- description and source-code
```javascript
function TreeNode(props) {
  _classCallCheck(this, TreeNode);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  ['onExpand', 'onCheck', 'onContextMenu', 'onMouseEnter', 'onMouseLeave', 'onDragStart', 'onDragEnter', 'onDragOver', 'onDragLeave
', 'onDrop', 'onDragEnd'].forEach(function (m) {
    _this[m] = _this[m].bind(_this);
  });
  _this.state = {
    dataLoading: false,
    dragNodeHighlight: false
  };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tree.TreeNode"></a>[module antd.Tree.TreeNode](#apidoc.module.antd.Tree.TreeNode)

#### <a name="apidoc.element.antd.Tree.TreeNode.TreeNode"></a>[function <span class="apidocSignatureSpan">antd.Tree.</span>TreeNode (props)](#apidoc.element.antd.Tree.TreeNode.TreeNode)
- description and source-code
```javascript
function TreeNode(props) {
  _classCallCheck(this, TreeNode);

  var _this = _possibleConstructorReturn(this, _React$Component.call(this, props));

  ['onExpand', 'onCheck', 'onContextMenu', 'onMouseEnter', 'onMouseLeave', 'onDragStart', 'onDragEnter', 'onDragOver', 'onDragLeave
', 'onDrop', 'onDragEnd'].forEach(function (m) {
    _this[m] = _this[m].bind(_this);
  });
  _this.state = {
    dataLoading: false,
    dragNodeHighlight: false
  };
  return _this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tree.TreeNode.prototype"></a>[module antd.Tree.TreeNode.prototype](#apidoc.module.antd.Tree.TreeNode.prototype)

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>componentDidMount ()](#apidoc.element.antd.Tree.TreeNode.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  if (!this.props.root._treeNodeInstances) {
    this.props.root._treeNodeInstances = [];
  }
  this.props.root._treeNodeInstances.push(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onCheck"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onCheck ()](#apidoc.element.antd.Tree.TreeNode.prototype.onCheck)
- description and source-code
```javascript
function onCheck() {
  this.props.root.onCheck(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onContextMenu"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onContextMenu (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onContextMenu)
- description and source-code
```javascript
function onContextMenu(e) {
  e.preventDefault();
  this.props.root.onContextMenu(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onDragEnd"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragEnd (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragEnd)
- description and source-code
```javascript
function onDragEnd(e) {
  e.stopPropagation();
  this.setState({
    dragNodeHighlight: false
  });
  this.props.root.onDragEnd(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onDragEnter"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragEnter (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragEnter)
- description and source-code
```javascript
function onDragEnter(e) {
  e.preventDefault();
  e.stopPropagation();
  this.props.root.onDragEnter(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onDragLeave"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragLeave (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragLeave)
- description and source-code
```javascript
function onDragLeave(e) {
  e.stopPropagation();
  this.props.root.onDragLeave(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onDragOver"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragOver (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragOver)
- description and source-code
```javascript
function onDragOver(e) {
  // todo disabled
  e.preventDefault();
  e.stopPropagation();
  this.props.root.onDragOver(e, this);
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onDragStart"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDragStart (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDragStart)
- description and source-code
```javascript
function onDragStart(e) {
  // console.log('dragstart', this.props.eventKey, e);
  // e.preventDefault();
  e.stopPropagation();
  this.setState({
    dragNodeHighlight: true
  });
  this.props.root.onDragStart(e, this);
  try {
    // ie throw error
    // firefox-need-it
    e.dataTransfer.setData('text/plain', '');
  } catch (error) {
    // empty
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onDrop"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onDrop (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onDrop)
- description and source-code
```javascript
function onDrop(e) {
  e.preventDefault();
  e.stopPropagation();
  this.setState({
    dragNodeHighlight: false
  });
  this.props.root.onDrop(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onExpand"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onExpand ()](#apidoc.element.antd.Tree.TreeNode.prototype.onExpand)
- description and source-code
```javascript
function onExpand() {
  var _this2 = this;

  var callbackPromise = this.props.root.onExpand(this);
  if (callbackPromise && (typeof callbackPromise === 'undefined' ? 'undefined' : _typeof(callbackPromise)) === 'object') {
    var setLoading = function setLoading(dataLoading) {
      _this2.setState({ dataLoading: dataLoading });
    };
    setLoading(true);
    callbackPromise.then(function () {
      setLoading(false);
    }, function () {
      setLoading(false);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onKeyDown"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onKeyDown (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onKeyDown)
- description and source-code
```javascript
function onKeyDown(e) {
  e.preventDefault();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onMouseEnter"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onMouseEnter (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onMouseEnter)
- description and source-code
```javascript
function onMouseEnter(e) {
  e.preventDefault();
  this.props.root.onMouseEnter(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onMouseLeave"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onMouseLeave (e)](#apidoc.element.antd.Tree.TreeNode.prototype.onMouseLeave)
- description and source-code
```javascript
function onMouseLeave(e) {
  e.preventDefault();
  this.props.root.onMouseLeave(e, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.onSelect"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>onSelect ()](#apidoc.element.antd.Tree.TreeNode.prototype.onSelect)
- description and source-code
```javascript
function onSelect() {
  this.props.root.onSelect(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>render ()](#apidoc.element.antd.Tree.TreeNode.prototype.render)
- description and source-code
```javascript
function render() {
  var _iconEleCls,
      _this3 = this;

  var props = this.props;
  var prefixCls = props.prefixCls;
  var expandedState = props.expanded ? 'open' : 'close';
  var iconState = expandedState;

  var canRenderSwitcher = true;
  var content = props.title;
  var newChildren = this.renderChildren(props);
  if (!newChildren || newChildren === props.children) {
    // content = newChildren;
    newChildren = null;
    if (!props.loadData || props.isLeaf) {
      canRenderSwitcher = false;
      iconState = 'docu';
    }
  }
  // For performance, does't render children into dom when '!props.expanded' (move to Animate)
  // if (!props.expanded) {
  //   newChildren = null;
  // }

  var iconEleCls = (_iconEleCls = {}, _defineProperty(_iconEleCls, prefixCls + '-iconEle', true), _defineProperty(_iconEleCls, prefixCls
 + '-icon_loading', this.state.dataLoading), _defineProperty(_iconEleCls, prefixCls + '-icon__' + iconState, true), _iconEleCls);

  var selectHandle = function selectHandle() {
    var icon = props.showIcon || props.loadData && _this3.state.dataLoading ? _react2["default"].createElement('span', { className
: (0, _classnames2["default"])(iconEleCls) }) : null;
    var title = _react2["default"].createElement(
      'span',
      { className: prefixCls + '-title' },
      content
    );
    var wrap = prefixCls + '-node-content-wrapper';
    var domProps = {
      className: wrap + ' ' + wrap + '-' + (iconState === expandedState ? iconState : 'normal')
    };
    if (!props.disabled) {
      if (props.selected || !props._dropTrigger && _this3.state.dragNodeHighlight) {
        domProps.className += ' ' + prefixCls + '-node-selected';
      }
      domProps.onClick = function (e) {
        e.preventDefault();
        if (props.selectable) {
          _this3.onSelect();
        }
        // not fire check event
        // if (props.checkable) {
        //   this.onCheck();
        // }
      };
      if (props.onRightClick) {
        domProps.onContextMenu = _this3.onContextMenu;
      }
      if (props.onMouseEnter) {
        domProps.onMouseEnter = _this3.onMouseEnter;
      }
      if (props.onMouseLeave) {
        domProps.onMouseLeave = _this3.onMouseLeave;
      }
      if (props.draggable) {
        domProps.className += ' draggable';
        if (ieOrEdge) {
          // ie bug!
          domProps.href = '#';
        }
        domProps.draggable = true;
        domProps['aria-grabbed'] = true;
        domProps.onDragStart = _this3.onDragStart;
      }
    }
    return _react2["default"].createElement(
      'a',
      _extends({ ref: 'selectHandle', title: typeof content === 'string' ? content : '' }, domProps),
      icon,
      title
    );
  };

  var liProps = {};
  if (props.draggable) {
    liProps.onDragEnter = this.onDragEnter;
    liProps.onDragOver = this.onDragOver;
    liProps.onDragLeave = this.onDragLeave;
    liProps.onDrop = this.onDrop;
    liProps.onDragEnd = this.onDragEnd;
  }

  var disabledCls = '';
  var dragOverCls = '';
  if (props.disabled) {
    disabledCls = prefixCls + '-treenode-disabled';
  } else if (props.dragOver) {
    dragOverCls = 'drag-over';
  } else if (props.dragOverGapTop) {
    dragOverCls = 'drag-over-gap-top';
  } else if (props.dragOverGapBottom) {
    dragOverCls = 'drag-over-gap-bottom';
  }

  var filterCls = props.filterTreeNode(this) ? 'filter-node' : '';

  var noopSwitcher = function noopSwitcher() {
    var _cls2;

    var cls = (_cls2 = {}, _defineProperty(_cls2, prefixCls + '-switcher', true), _defineProperty(_cls2, prefixCls + '-switcher-
noop', true), _cls2);
    if (props.showLine) {
      cls[prefixCls + '-center_docu'] = !props.last;
      cls[prefixCls + '-bottom_docu'] = props.last;
    } else {
      cls[prefixCls + '-noline_docu'] = true;
    }
    return _react2["default"].createElement('span', { className: (0, _classnames2["default"])(cls) });
  };

  return _react2["default"].createElement(
    'li',
    _extends({}, liProps, { ref: 'li',
      className: (0, _classnames2["default"])(props.className, disabledCls, dragOverCls, f ...
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.renderCheckbox"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>renderCheckbox (props)](#apidoc.element.antd.Tree.TreeNode.prototype.renderCheckbox)
- description and source-code
```javascript
function renderCheckbox(props) {
  var prefixCls = props.prefixCls;
  var checkboxCls = _defineProperty({}, prefixCls + '-checkbox', true);
  if (props.checked) {
    checkboxCls[prefixCls + '-checkbox-checked'] = true;
  } else if (props.halfChecked) {
    checkboxCls[prefixCls + '-checkbox-indeterminate'] = true;
  }
  var customEle = null;
  if (typeof props.checkable !== 'boolean') {
    customEle = props.checkable;
  }
  if (props.disabled || props.disableCheckbox) {
    checkboxCls[prefixCls + '-checkbox-disabled'] = true;
    return _react2["default"].createElement(
      'span',
      { ref: 'checkbox', className: (0, _classnames2["default"])(checkboxCls) },
      customEle
    );
  }
  return _react2["default"].createElement(
    'span',
    { ref: 'checkbox',
      className: (0, _classnames2["default"])(checkboxCls),
      onClick: this.onCheck
    },
    customEle
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.renderChildren"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>renderChildren (props)](#apidoc.element.antd.Tree.TreeNode.prototype.renderChildren)
- description and source-code
```javascript
function renderChildren(props) {
  var renderFirst = this.renderFirst;
  this.renderFirst = 1;
  var transitionAppear = true;
  if (!renderFirst && props.expanded) {
    transitionAppear = false;
  }
  var children = props.children ? (0, _toArray2["default"])(props.children) : props.children;
  var newChildren = children;
  if (children && (Array.isArray(children) && children.every(function (item) {
    return item.type && item.type.isTreeNode;
  }) || children.type && children.type.isTreeNode)) {
    var _cls;

    var cls = (_cls = {}, _defineProperty(_cls, props.prefixCls + '-child-tree', true), _defineProperty(_cls, props.prefixCls + '-
child-tree-open', props.expanded), _cls);
    if (props.showLine) {
      cls[props.prefixCls + '-line'] = !props.last;
    }
    var animProps = {};
    if (props.openTransitionName) {
      animProps.transitionName = props.openTransitionName;
    } else if (_typeof(props.openAnimation) === 'object') {
      animProps.animation = (0, _objectAssign2["default"])({}, props.openAnimation);
      if (!transitionAppear) {
        delete animProps.animation.appear;
      }
    }
    newChildren = _react2["default"].createElement(
      _rcAnimate2["default"],
      _extends({}, animProps, {
        showProp: 'data-expanded',
        transitionAppear: transitionAppear,
        component: ''
      }),
      !props.expanded ? null : _react2["default"].createElement(
        'ul',
        { className: (0, _classnames2["default"])(cls), 'data-expanded': props.expanded },
        _react2["default"].Children.map(children, function (item, index) {
          return props.root.renderTreeNode(item, index, props.pos);
        }, props.root)
      )
    );
  }
  return newChildren;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Tree.TreeNode.prototype.renderSwitcher"></a>[function <span class="apidocSignatureSpan">antd.Tree.TreeNode.prototype.</span>renderSwitcher (props, expandedState)](#apidoc.element.antd.Tree.TreeNode.prototype.renderSwitcher)
- description and source-code
```javascript
function renderSwitcher(props, expandedState) {
  var prefixCls = props.prefixCls;
  var switcherCls = _defineProperty({}, prefixCls + '-switcher', true);
  if (!props.showLine) {
    switcherCls[prefixCls + '-noline_' + expandedState] = true;
  } else if (props.pos === '0-0') {
    switcherCls[prefixCls + '-roots_' + expandedState] = true;
  } else {
    switcherCls[prefixCls + '-center_' + expandedState] = !props.last;
    switcherCls[prefixCls + '-bottom_' + expandedState] = props.last;
  }
  if (props.disabled) {
    switcherCls[prefixCls + '-switcher-disabled'] = true;
    return _react2["default"].createElement('span', { className: (0, _classnames2["default"])(switcherCls) });
  }
  return _react2["default"].createElement('span', { className: (0, _classnames2["default"])(switcherCls), onClick: this.onExpand
 });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Tree.prototype"></a>[module antd.Tree.prototype](#apidoc.module.antd.Tree.prototype)

#### <a name="apidoc.element.antd.Tree.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Tree.prototype.</span>render ()](#apidoc.element.antd.Tree.prototype.render)
- description and source-code
```javascript
function render() {
    var props = this.props;
    var prefixCls = props.prefixCls,
        className = props.className,
        showLine = props.showLine;

    var checkable = props.checkable;
    var classString = (0, _classnames2["default"])((0, _defineProperty3["default"])({}, prefixCls + '-show-line', !!showLine), className
);
    return _react2["default"].createElement(
        _rcTree2["default"],
        (0, _extends3["default"])({}, props, { className: classString, checkable: checkable ? _react2["default"].createElement('
span', { className: prefixCls + '-checkbox-inner' }) : checkable }),
        this.props.children
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.TreeSelect"></a>[module antd.TreeSelect](#apidoc.module.antd.TreeSelect)

#### <a name="apidoc.element.antd.TreeSelect.TreeSelect"></a>[function <span class="apidocSignatureSpan">antd.</span>TreeSelect ()](#apidoc.element.antd.TreeSelect.TreeSelect)
- description and source-code
```javascript
function _a() {
    (0, _classCallCheck3["default"])(this, _a);
    return (0, _possibleConstructorReturn3["default"])(this, _Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.TreeSelect.contextTypes"></a>[module antd.TreeSelect.contextTypes](#apidoc.module.antd.TreeSelect.contextTypes)

#### <a name="apidoc.element.antd.TreeSelect.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.TreeSelect.contextTypes.</span>antLocale ()](#apidoc.element.antd.TreeSelect.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.TreeSelect.prototype"></a>[module antd.TreeSelect.prototype](#apidoc.module.antd.TreeSelect.prototype)

#### <a name="apidoc.element.antd.TreeSelect.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.TreeSelect.prototype.</span>getLocale ()](#apidoc.element.antd.TreeSelect.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var antLocale = this.context.antLocale;

    var localeFromContext = antLocale && antLocale[componentName];
    var localeFromProps = this.props.locale || {};
    return (0, _extends3["default"])({}, defaultLocale, localeFromContext || {}, localeFromProps);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Upload"></a>[module antd.Upload](#apidoc.module.antd.Upload)

#### <a name="apidoc.element.antd.Upload.Upload"></a>[function <span class="apidocSignatureSpan">antd.</span>Upload (props)](#apidoc.element.antd.Upload.Upload)
- description and source-code
```javascript
function Upload(props) {
    (0, _classCallCheck3["default"])(this, Upload);

    var _this = (0, _possibleConstructorReturn3["default"])(this, _React$Component.call(this, props));

    _this.onStart = function (file) {
        var targetItem = void 0;
        var nextFileList = _this.state.fileList.concat();
        if (file.length > 0) {
            targetItem = file.map(function (f) {
                var fileObject = (0, _utils.fileToObject)(f);
                fileObject.status = 'uploading';
                return fileObject;
            });
            nextFileList = nextFileList.concat(targetItem);
        } else {
            targetItem = (0, _utils.fileToObject)(file);
            targetItem.status = 'uploading';
            nextFileList.push(targetItem);
        }
        _this.onChange({
            file: targetItem,
            fileList: nextFileList
        });
        // fix ie progress
        if (!window.FormData) {
            _this.autoUpdateProgress(0, targetItem);
        }
    };
    _this.onSuccess = function (response, file) {
        _this.clearProgressTimer();
        try {
            if (typeof response === 'string') {
                response = JSON.parse(response);
            }
        } catch (e) {}
        var fileList = _this.state.fileList;
        var targetItem = (0, _utils.getFileItem)(file, fileList);
        // removed
        if (!targetItem) {
            return;
        }
        targetItem.status = 'done';
        targetItem.response = response;
        _this.onChange({
            file: (0, _extends3["default"])({}, targetItem),
            fileList: fileList
        });
    };
    _this.onProgress = function (e, file) {
        var fileList = _this.state.fileList;
        var targetItem = (0, _utils.getFileItem)(file, fileList);
        // removed
        if (!targetItem) {
            return;
        }
        targetItem.percent = e.percent;
        _this.onChange({
            event: e,
            file: (0, _extends3["default"])({}, targetItem),
            fileList: _this.state.fileList
        });
    };
    _this.onError = function (error, response, file) {
        _this.clearProgressTimer();
        var fileList = _this.state.fileList;
        var targetItem = (0, _utils.getFileItem)(file, fileList);
        // removed
        if (!targetItem) {
            return;
        }
        targetItem.error = error;
        targetItem.response = response;
        targetItem.status = 'error';
        _this.onChange({
            file: (0, _extends3["default"])({}, targetItem),
            fileList: fileList
        });
    };
    _this.handleManualRemove = function (file) {
        _this.refs.upload.abort(file);
        file.status = 'removed'; // eslint-disable-line
        _this.handleRemove(file);
    };
    _this.onChange = function (info) {
        if (!('fileList' in _this.props)) {
            _this.setState({ fileList: info.fileList });
        }
        var onChange = _this.props.onChange;

        if (onChange) {
            onChange(info);
        }
    };
    _this.onFileDrop = function (e) {
        _this.setState({
            dragState: e.type
        });
    };
    _this.state = {
        fileList: _this.props.fileList || _this.props.defaultFileList || [],
        dragState: 'drop'
    };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.Dragger"></a>[function <span class="apidocSignatureSpan">antd.Upload.</span>Dragger ()](#apidoc.element.antd.Upload.Dragger)
- description and source-code
```javascript
function Dragger() {
    (0, _classCallCheck3["default"])(this, Dragger);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Upload.Dragger"></a>[module antd.Upload.Dragger](#apidoc.module.antd.Upload.Dragger)

#### <a name="apidoc.element.antd.Upload.Dragger.Dragger"></a>[function <span class="apidocSignatureSpan">antd.Upload.</span>Dragger ()](#apidoc.element.antd.Upload.Dragger.Dragger)
- description and source-code
```javascript
function Dragger() {
    (0, _classCallCheck3["default"])(this, Dragger);
    return (0, _possibleConstructorReturn3["default"])(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Upload.Dragger.prototype"></a>[module antd.Upload.Dragger.prototype](#apidoc.module.antd.Upload.Dragger.prototype)

#### <a name="apidoc.element.antd.Upload.Dragger.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Upload.Dragger.prototype.</span>render ()](#apidoc.element.antd.Upload.Dragger.prototype.render)
- description and source-code
```javascript
function render() {
    var props = this.props;

    return _react2["default"].createElement(_Upload2["default"], (0, _extends3["default"])({}, props, { type: 'drag', style: { height
: props.height } }));
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.Upload.contextTypes"></a>[module antd.Upload.contextTypes](#apidoc.module.antd.Upload.contextTypes)

#### <a name="apidoc.element.antd.Upload.contextTypes.antLocale"></a>[function <span class="apidocSignatureSpan">antd.Upload.contextTypes.</span>antLocale ()](#apidoc.element.antd.Upload.contextTypes.antLocale)
- description and source-code
```javascript
antLocale = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Upload.defaultProps"></a>[module antd.Upload.defaultProps](#apidoc.module.antd.Upload.defaultProps)

#### <a name="apidoc.element.antd.Upload.defaultProps.beforeUpload"></a>[function <span class="apidocSignatureSpan">antd.Upload.defaultProps.</span>beforeUpload ()](#apidoc.element.antd.Upload.defaultProps.beforeUpload)
- description and source-code
```javascript
function T() {
    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.Upload.prototype"></a>[module antd.Upload.prototype](#apidoc.module.antd.Upload.prototype)

#### <a name="apidoc.element.antd.Upload.prototype.autoUpdateProgress"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>autoUpdateProgress (_, file)](#apidoc.element.antd.Upload.prototype.autoUpdateProgress)
- description and source-code
```javascript
function autoUpdateProgress(_, file) {
    var _this2 = this;

    var getPercent = (0, _utils.genPercentAdd)();
    var curPercent = 0;
    this.clearProgressTimer();
    this.progressTimer = setInterval(function () {
        curPercent = getPercent(curPercent);
        _this2.onProgress({
            percent: curPercent
        }, file);
    }, 200);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.prototype.clearProgressTimer"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>clearProgressTimer ()](#apidoc.element.antd.Upload.prototype.clearProgressTimer)
- description and source-code
```javascript
function clearProgressTimer() {
    clearInterval(this.progressTimer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.antd.Upload.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
    if ('fileList' in nextProps) {
        this.setState({
            fileList: nextProps.fileList || []
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>componentWillUnmount ()](#apidoc.element.antd.Upload.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
    this.clearProgressTimer();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.prototype.getLocale"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>getLocale ()](#apidoc.element.antd.Upload.prototype.getLocale)
- description and source-code
```javascript
function getLocale() {
    var locale = {};
    if (this.context.antLocale && this.context.antLocale.Upload) {
        locale = this.context.antLocale.Upload;
    }
    return (0, _objectAssign2["default"])({}, defaultLocale, locale, this.props.locale);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.prototype.handleRemove"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>handleRemove (file)](#apidoc.element.antd.Upload.prototype.handleRemove)
- description and source-code
```javascript
function handleRemove(file) {
    var onRemove = this.props.onRemove;
    // Prevent removing file

    var onRemoveReturnValue = onRemove && onRemove(file);
    if (onRemoveReturnValue === false) {
        return;
    }
    var removedFileList = (0, _utils.removeFileItem)(file, this.state.fileList);
    if (removedFileList) {
        this.onChange({
            file: file,
            fileList: removedFileList
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.Upload.prototype.render"></a>[function <span class="apidocSignatureSpan">antd.Upload.prototype.</span>render ()](#apidoc.element.antd.Upload.prototype.render)
- description and source-code
```javascript
function render() {
    var _classNames2;

    var _props = this.props,
        _props$prefixCls = _props.prefixCls,
        prefixCls = _props$prefixCls === undefined ? '' : _props$prefixCls,
        showUploadList = _props.showUploadList,
        listType = _props.listType,
        onPreview = _props.onPreview,
        type = _props.type,
        disabled = _props.disabled,
        children = _props.children,
        className = _props.className;

    var rcUploadProps = (0, _objectAssign2["default"])({}, {
        onStart: this.onStart,
        onError: this.onError,
        onProgress: this.onProgress,
        onSuccess: this.onSuccess
    }, this.props);
    delete rcUploadProps.className;
    var showRemoveIcon = showUploadList.showRemoveIcon,
        showPreviewIcon = showUploadList.showPreviewIcon;

    var uploadList = showUploadList ? _react2["default"].createElement(_UploadList2["default"], { listType: listType, items: this
.state.fileList, onPreview: onPreview, onRemove: this.handleManualRemove, showRemoveIcon: showRemoveIcon, showPreviewIcon: showPreviewIcon
, locale: this.getLocale() }) : null;
    if (type === 'drag') {
        var _classNames;

        var dragCls = (0, _classnames2["default"])(prefixCls, (_classNames = {}, (0, _defineProperty3["default"])(_classNames, prefixCls
 + '-drag', true), (0, _defineProperty3["default"])(_classNames, prefixCls + '-drag-uploading', this.state.fileList.some(function
 (file) {
            return file.status === 'uploading';
        })), (0, _defineProperty3["default"])(_classNames, prefixCls + '-drag-hover', this.state.dragState === 'dragover'), (0,
_defineProperty3["default"])(_classNames, prefixCls + '-disabled', disabled), _classNames));
        return _react2["default"].createElement(
            'span',
            { className: className },
            _react2["default"].createElement(
                'div',
                { className: dragCls, onDrop: this.onFileDrop, onDragOver: this.onFileDrop, onDragLeave: this.onFileDrop },
                _react2["default"].createElement(
                    _rcUpload2["default"],
                    (0, _extends3["default"])({}, rcUploadProps, { ref: 'upload', className: prefixCls + '-btn' }),
                    _react2["default"].createElement(
                        'div',
                        { className: prefixCls + '-drag-container' },
                        children
                    )
                )
            ),
            uploadList
        );
    }
    var uploadButtonCls = (0, _classnames2["default"])(prefixCls, (_classNames2 = {}, (0, _defineProperty3["default"])(_classNames2
, prefixCls + '-select', true), (0, _defineProperty3["default"])(_classNames2, prefixCls + '-select-' + listType, true), (0, _defineProperty3
["default"])(_classNames2, prefixCls + '-disabled', disabled), _classNames2));
    var uploadButton = _react2["default"].createElement(
        'div',
        { className: uploadButtonCls, style: { display: children ? '' : 'none' } },
        _react2["default"].createElement(_rcUpload2["default"], (0, _extends3["default"])({}, rcUploadProps, { ref: 'upload' }))
    );
    if (listType === 'picture-card') {
        return _react2["default"].createElement(
            'span',
            { className: className },
            uploadList,
            uploadButton
        );
    }
    return _react2["default"].createElement(
        'span',
        { className: className },
        uploadButton,
        uploadList
    );
}
```
- example usage
```shell
...
npm install antd
'''

## Usage

'''jsx
import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);
'''

And import style manually:

'''jsx
import 'antd/dist/antd.css';  // or 'antd/dist/antd.less'
'''
...
```



# <a name="apidoc.module.antd.message"></a>[module antd.message](#apidoc.module.antd.message)

#### <a name="apidoc.element.antd.message.config"></a>[function <span class="apidocSignatureSpan">antd.message.</span>config (options)](#apidoc.element.antd.message.config)
- description and source-code
```javascript
function config(options) {
    if (options.top !== undefined) {
        defaultTop = options.top;
        messageInstance = null; // delete messageInstance for new defaultTop
    }
    if (options.duration !== undefined) {
        defaultDuration = options.duration;
    }
    if (options.prefixCls !== undefined) {
        prefixCls = options.prefixCls;
    }
    if (options.getContainer !== undefined) {
        getContainer = options.getContainer;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.destroy"></a>[function <span class="apidocSignatureSpan">antd.message.</span>destroy ()](#apidoc.element.antd.message.destroy)
- description and source-code
```javascript
function destroy() {
    if (messageInstance) {
        messageInstance.destroy();
        messageInstance = null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.error"></a>[function <span class="apidocSignatureSpan">antd.message.</span>error (content, duration, onClose)](#apidoc.element.antd.message.error)
- description and source-code
```javascript
function error(content, duration, onClose) {
    return notice(content, duration, 'error', onClose);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.info"></a>[function <span class="apidocSignatureSpan">antd.message.</span>info (content, duration, onClose)](#apidoc.element.antd.message.info)
- description and source-code
```javascript
function info(content, duration, onClose) {
    return notice(content, duration, 'info', onClose);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.loading"></a>[function <span class="apidocSignatureSpan">antd.message.</span>loading (content, duration, onClose)](#apidoc.element.antd.message.loading)
- description and source-code
```javascript
function loading(content, duration, onClose) {
    return notice(content, duration, 'loading', onClose);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.success"></a>[function <span class="apidocSignatureSpan">antd.message.</span>success (content, duration, onClose)](#apidoc.element.antd.message.success)
- description and source-code
```javascript
function success(content, duration, onClose) {
    return notice(content, duration, 'success', onClose);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.warn"></a>[function <span class="apidocSignatureSpan">antd.message.</span>warn (content, duration, onClose)](#apidoc.element.antd.message.warn)
- description and source-code
```javascript
function warn(content, duration, onClose) {
    return notice(content, duration, 'warning', onClose);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.message.warning"></a>[function <span class="apidocSignatureSpan">antd.message.</span>warning (content, duration, onClose)](#apidoc.element.antd.message.warning)
- description and source-code
```javascript
function warning(content, duration, onClose) {
    return notice(content, duration, 'warning', onClose);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.antd.notification"></a>[module antd.notification](#apidoc.module.antd.notification)

#### <a name="apidoc.element.antd.notification.close"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>close (key)](#apidoc.element.antd.notification.close)
- description and source-code
```javascript
function close(key) {
    if (notificationInstance) {
        notificationInstance.removeNotice(key);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.config"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>config (options)](#apidoc.element.antd.notification.config)
- description and source-code
```javascript
function config(options) {
    var duration = options.duration,
        placement = options.placement,
        bottom = options.bottom,
        top = options.top;

    if (placement !== undefined) {
        defaultPlacement = placement;
    }
    if (bottom !== undefined) {
        defaultBottom = bottom;
    }
    if (top !== undefined) {
        defaultTop = top;
    }
    // delete notificationInstance
    if (placement !== undefined || bottom !== undefined || top !== undefined) {
        notificationInstance = null;
    }
    if (duration !== undefined) {
        defaultDuration = duration;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.destroy"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>destroy ()](#apidoc.element.antd.notification.destroy)
- description and source-code
```javascript
function destroy() {
    if (notificationInstance) {
        notificationInstance.destroy();
        notificationInstance = null;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.error"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>error (args)](#apidoc.element.antd.notification.error)
- description and source-code
```javascript
error = function (args) {
    return api.open((0, _objectAssign2["default"])({}, args, { type: type }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.info"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>info (args)](#apidoc.element.antd.notification.info)
- description and source-code
```javascript
info = function (args) {
    return api.open((0, _objectAssign2["default"])({}, args, { type: type }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.open"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>open (args)](#apidoc.element.antd.notification.open)
- description and source-code
```javascript
function open(args) {
    notice(args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.success"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>success (args)](#apidoc.element.antd.notification.success)
- description and source-code
```javascript
success = function (args) {
    return api.open((0, _objectAssign2["default"])({}, args, { type: type }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.warn"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>warn (args)](#apidoc.element.antd.notification.warn)
- description and source-code
```javascript
warn = function (args) {
    return api.open((0, _objectAssign2["default"])({}, args, { type: type }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.antd.notification.warning"></a>[function <span class="apidocSignatureSpan">antd.notification.</span>warning (args)](#apidoc.element.antd.notification.warning)
- description and source-code
```javascript
warning = function (args) {
    return api.open((0, _objectAssign2["default"])({}, args, { type: type }));
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
