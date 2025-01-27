# CHANGELOG

## v4.2.0-alpha.3

- chore: Fix CI release action (#47)

## v4.2.0-alpha.2

- chore: Fix CI workflows (#46)
- build(deps): bump nanoid from 3.3.7 to 3.3.8 (#39)

## v4.2.0-alpha.1

- feat(geospatial): Add makeOBBFromRegion() (#43) (Co-authored-by: Raimund Schnürer <raimund.schnurer@epfl.ch>)
- chore: Bump lerna to 4.2.0-alpha.0. Fix CI. Modernize dependencies. (#41)
- build(deps): bump vite from 4.5.3 to 4.5.5 (#34)
- chore: Fix website build (#33)

## v4.1.0

- Website home page pass
- Bump dev-tools
- Try fix website publish
- Create website.yml
- build(deps): bump semver from 5.7.1 to 5.7.2 (#31)
- build(deps): bump word-wrap from 1.2.3 to 1.2.5 (#30)
- build(deps-dev): bump webpack from 4.46.0 to 5.94.0 (#29)

## v4.1.0-alpha.9

- chore: switch to @vis.gl/dev-tools and CI release
- feat(types): Sized numeric arrays (#16)

## v4.1.0-alpha.3
## v4.1.0-alpha.2

- chore: bump to ocular-dev-tools@2.0.0-alpha.34
- chore: Licenses (#15)
- chore: Clean up types (#14)

## v4.1.0-alpha.1

- feat: Add sized array types (#11)
- feat(types): Add bounds types (#12)
- chore: Add SPDX license headers (#10)
- Remove legacy viewport-mercator-project module (#9)
- Restore browser test (#8)
- fix(dggs-s2): Replace long module with bigint (#6)
- fix(types): isTypedArray now performs type narrowing (#3)
- chore: github test workflow (#4)
- chore: Move to yarn@4.3.1, node@20.15.1, ocular-dev-tools@alpha.33 (#2)
- chore: Remove dependency on long
- chore: Remove dependency on long

## v4.0.1

- chore: Bump probe.gl (#8)
- chore: Fix publint warnings (#14)
- fix: Return type of `rotate` in `Matrix3` (#13)
- Upgrade ocular-dev-tools (#17)

## v4.0.0

- docs: Update docs for 4.0 (#7)

## v4.0.0-beta.1

- chore: Remove gl-matrix import (#6)
- chore: Rename DGGS modules (#5)
- chore: Node 18 (#3)

## 4.0.0-alpha.4

- fix(4.0) add exports field to ES module package.json (#335)

## 4.0.0-alpha.3

- fix(core): Fix gl-matrix imports (#334)

## 4.0.0-alpha.2

- chore(core): Fork gl-matrix (#333)
- chore: Bump dev tools (#316)

## 4.0.0-alpha.1

- chore: Bump lerna.json to 4.0.0-alpha.0
- chore: switch to pure ES module (v4.0) (#315)

## 3.6.3

- [web-mercator] Fix reverse top/bottom padding in fitBounds (#302)

## 3.6.2

- Remove enum exports (#298)

## 3.6.1

- [web-mercator] Add unitsPerMeter util (#296)
- [web-mercator] Account for elevation and offset when calculating far z (#295)

## 3.6.0

## 3.6.0-alpha.8

- Fix Matrix4.transform type (#294)

## 3.6.0-alpha.7

- [sun] Fix position calculation (#293)

## 3.6.0-alpha.6

- lint (#292)
- [polygon] utility functions accept typed array inputs (#291)

## 3.6.0-alpha.5

- Fix core type errors (#286)
- Fix type errors in common (#285)

## 3.6.0-alpha.4

- Fix core package types entry point (#283)

## 3.6.0-alpha.3

- Fix Matrix4.lookAt types (#281)

## 3.6.0-alpha.2

- (HEAD -> master, origin/master, origin/HEAD) chore(core): lint (#280)
- Remove duplicate types (#279)
- chore(polygon): improve typings (#278)
- Add typing for gl-matrix (#277)
- chore: convert core module to typescript (#260)

## 3.6.0-alpha.1

- chore: Import '@math.gl/core' instead of 'math.gl' (#258)
- chore: Add ts build (#257)
- chore: Move polygon module to .ts (#256)
- Bump url-parse from 1.5.1 to 1.5.3 (#254)
- chore: Move .d.ts files to .ts (#255)

## 3.5.6

- Pin gl-matrix to ~3.3.0 (#253)
- fix(core): Euler.getQuaternion never use rotation order (#251)

## 3.5.5

- [fix] Improve web mercator viewport normalization (#250)

## v3.5.4

- [fix] BoundingSphere.distanceTo (#248)
- [fix] makeOrientedBoundingBoxFromPoints crash (#247)
- [fix] makeBoundingSphereFromPoints inconsistent result (#246)

## v3.5.3

- Export altitudeToFovy & fovyToAltitude (#244)

## v3.5.2

- chore: bump probe.gl (#243)
- chore: 3.5 docs (#242)
- Fix typo (#241)

## v3.5.1

- Extend web mercator viewport to support fovy parameter (#240)

# v3.5.0-beta.1

- chore: Bump ocular@1.0.0-alpha.7 (#238)
- viewport-mercator-project@7.0.3
- WebMercatorViewport supports camera meter offset (#235)
- chore: Use babel-register to run tests and bench (#236)
- feat(culling): Add BoundingVolume interface (#227)
- chore(polygon): Move earcut test data (#234)
- Add tests and types for Polygon & earcut (#224)
- feat(culling): Addd transforms to bounding boxes (#231)
- chore: Add back CI versions, fix CI target (#233)
- chore: Fix CI coverage (#232)
- Bounding box transforms (#226)
- chore: Upgrade node CI versions to 12, 14, 16 (#222)
- chore: upgrade ocular (#221)

# v3.5.0-alpha.1

- Add earcut (#219)
- Faster polygon area (#218)
- Drop es6 entry points (#217)
- Update build targets (#215)
- Add a more detailed type definition for `getLocationAtPoint()`. (#201)
- Bounding Box From Points - Fix for scaling method (#206)
- ESLint fix in math-utils.js file (#207)
- Handle missing log2 in IE 11 (#204)
- [viewport-mercator-project] v7.0.2
- [viewport-mercator-project] re-export typescript types (#198)
- Fixes matrix4 decompose return types (#199)
- Fix lookat types (#197)
- documentation pass
- Transformation docs (#196)

## v3.4.1 - Jan 7, 2020

- chore: bump babel/runtime version to fix mjs issue (#193)
- chore: Cleanup READMEs and eslint defs (#192)
- feat: geoid module (#191)

## v3.4.0-alpha.1 - Dec 14, 2020

- [Polygon] Add support for flat arrays for polygons (#186)

## v3.3.2 - Dec 1, 2020

- [Perf] replace concat to improve cutPolygonByGrid performance (#182)

## v3.3.1 - Nov 15, 2020

- improve polygon subdivision precision (#180)

## v3.3.0 - Oct 9, 2020

## v3.3.0-beta.2 - Oct 7, 2020

- culling: construct obb from quaternion based obb (#172)
- culling: enhance quanternion based methods (#173)

## v3.3.0-beta.1 - Sep 26, 2020

- [Polygon] safety check in edge cases (#169)
- Bind project/unproject functions in Proj4Projection (#165)

## v3.3.0-alpha.2 - Aug 25, 2020

- Proj updates (#163)

## v3.3.0-alpha.1 - Aug 14, 2020

- proj4: new module for coordinate system conversion (#161)
- Bump elliptic from 6.5.1 to 6.5.3 (#160)
- Bump lodash from 4.17.15 to 4.17.19 (#159)

## v3.2.2 - July 7, 2020

- Update SegmentVisitor in polygon.d.ts

## v3.2.1 - June 18, 2020

- Upgrade dependencies

## v3.2.0 - June 18, 2020

## v3.2.0-alpha.5 - June 12, 2020

- [polygon] Fix edgeType bug (#152)

## v3.2.0-alpha.4 - June 12, 2020

- cutPolygonByGrid: add option to generate edge type flags (#151)

## v3.2.0-alpha.3 - May 14, 2020

- [web-mercator] Add getBounds utility (#146)
- Fix the bounds type for FitBoundsOptions (#149)
- fix build script (#148)
- Refactor WebMercatorViewport (#145)
- Clean up bounding volume classes and docs (#144)
- Fix web mercator projection far plane at high pitch (#142)
- Restore default export of @math.gl/web-mercator (#141)

## v3.2.0-alpha.2 - Apr 12, 2020

- Add typescript definitions for the polygon module (#140)
- [polygon] utils for geometries crossing the 180th meridian (#139)
- Add subdivision utilities to polygon module (#136)
- Add polygon module (#131)

## v3.2.0-alpha.1 - Mar 23, 2020

- typescript: tooling and initial type definitions (#132)
- typescript: Prep diff, makes JavaScript code typescript compatible (#129)
- web-mercator: typescript fixes (#128)
- typescript: linter fixes (#127)
- "soft" typescript checking of core module (#83)

## v3.1.5 - May 11, 2020

- Remove TypeScript definitions (#148)

## v3.1.4 - May 7, 2020

- Fix web mercator projection far plane at high pitch (#142)

## v3.1.3 - Jan 2, 2020

- [Fix] getFlyToDuration returns NaN when transitioning to same viewport center (#125)

## v3.1.2 - Dec 20, 2019

- Fix various culling issues (#124)

## v3.1.1 - Dec 16, 2019

- fix dependencies (#122)

## v3.1.0 - Dec 16, 2019

- fix equals (#120)

## v3.1.0-alpha.1 - Nov 4, 2019

- Rename viewport-mercator-project to @math.gl/web-mercator (#116)
- [viewport-mercator-project] use zoom-independent world space (#118)
- Add sun module (#114)
- Port sun calculations from deck (#111)
- Fixes for 3D tiles (#112)


## v3.0.0 - Sep 13, 2019

## v3.0.0-beta.3 - Aug 26, 2019

- Add getRotation return a Matrix3 object (#95)

## v3.0.0-beta.2 - Jul 24, 2019

- @math.gl/culling: Frustum classes to enable CullingVolume tests (#91)
- @math.gl/culling: AxisAlignedBoundingBox (#86)

## v3.0.0-beta.1 - Jul 1, 2019

## v3.0.0-alpha.6 - Jun 27, 2019

- add isWGS84 (#85)

## v3.0.0-alpha.5 - Jun 26, 2019

- fix cartesianToCartographic (#84)

## v3.0.0-alpha.4 - Jun 22, 2019

## v3.0.0-alpha.3 - Jun 11, 2019

## v3.0.0-alpha.2 - Jun 11, 2019

## v3.0.0-alpha.1 - Jun 11, 2019

- @math.gl/culling (#71)
- core: Matrix/Vector API alignment and performance tuning (#74)
- core: `transform` API overhaul (#72)
- Update docs and license (#70)
- @math.gl/geospatial: new module, initial commit (#66)
- Bump ocular-dev-tools to publish LICENSE (#68)
- Matrix4: Passes three.js test suite (#62)
- core: prep for geospatial (#65)
- Perf: Array base-class initialization perf improvements (#64)
- New methods: `Matrix.setColumn`/`getColumn` (#57)
- Monorepo dev setup (#55)


## v2.3.2 - May 30, 2019

- Readme hotfix (#49)
- Add scale factor support to Matrix3 and Matrix4 (#44)
- Implement matrix3 (#41)


## v2.3.0 - Jan 29, 2019

## v2.3.0-beta.2 - Jan 24, 2019

- Test coordinate transforms between poses (#39)
- Decouple Quaternion from Euler to optimize tree-shaking (#38)
- Use ocular-dev-tools instead of local dev scripts. (#37)- 

## v2.3.0-beta.1 - Jan 11, 2019

- Quaternion multiplication: b would be undefined (#35)
- Support quaternion to euler conversion (#31)
- Migrate to original gl-matrix package (#34)

## v2.2.0 - Sep 20, 2018 

- Use `@babel/runtime`
- Use babel 7
- FIX: `isArray` handles typed arrays correctly

## v2.1.0 - Sep 6, 2018 

- Support reconstructing Pose from serialized/deserialized props (#27)
- Fix Matrix4.setElement() when columnMajor = true.

## v2.1.0-alpha.1 - July 29, 2018

- Enable "sideEffects" in package.json to improve tree-shaking
- Delete comments in generated code
- Reuse x,y accessors in Vector

## v2.0.0 - June 25

- Rename experimental classes to use underscore (_).

## v1.2.1 - May 21, 2018

- Add `lerp` utility function

## v1.2.0 - May 4, 2018

- Add experimental Pose class

## v1.1.3 - Apr 16, 2018

- Matrix4 restore default arguments to setters 


## v1.1.2 - Apr 16, 2018

- Matrix4 fixes to regressions caused by code size reduction


## v1.1.1 - Apr 16, 2018

- Remove babel-minify to restore source maps


## v1.1.0 - Apr 16, 2018

- Upgrade to babel 7 (#19)
- Add Polygon class implementing Shoelace algorithm (#18)
- Improve error messages (#17)
- Add back Euler as experimental export
- Size reduction: Shared code moved from `Vector*` to `Vector` etc.
- Size reduction: Experimental Euler class no longer exported in index.js
- Size reduction: yarn test-size command
- Size reduction: new esnext main field, with untranspiled code.
- THREE.js Compatibility - doc and mew methods (experimental)
- THREE.js Compability - add test suites, run "unmodified" on math.gl classes


## v1.0

### 1.0.4 (Mar 2, 2018)
- FIX: github url link on npmjs.org

### 1.0.3 (Jan 17, 2018)
- FIX: Matrix4.rotateAxis
- FIX: github URL

### 1.0.2 (Jan 11, 2018)
- FIX: Vector3.len throws error
- FIX: Vector3.normalize throws error
- FIX: Vector3.dot

### 1.0.1 (Jan 9, 2018)
- FIX: missing Vector3.distance



# OLDER PRERELEASES

### v1.1.0-alpha.2
- Add back Euler as experimental export

### v1.1.0-alpha.1
- Size reduction: Shared code moved from `Vector*` to `Vector` etc.
- Size reduction: Experimental Euler class no longer exported in index.js
- Size reduction: yarn test-size command
- Size reduction: new esnext main field, with untranspiled code.

- THREE.js Compatibility - doc and mew methods (experimental)
- THREE.js Compability - add test suites, run "unmodified" on math.gl classes


## v1.0

### v1.0.0-alpha.7
- Website overhaul
- Add Uber license

### 1.0.0-alpha.6
- Matrix4 transforms
- Improved print functions
- Docs (coordinates etc)

### 1.0.0-alpha.5
- SphericalCoordinates overhaul
- Test cases

### 1.0.0-alpha.5
- Add roll/pitch/yaw getters/setters to `Euler`

### 1.0.0-alpha.4
- Vector3.rotate{X,Y,Z} now takes named arguments
- Doc overhaul
- Euler and Spherical are experimental exports

### 1.0.0-alpha.3
- Add Vector3.rotate{X,Y,Z}

### 1.0.0-alpha.2
- Docs
- Fix to Vector* add, subtract, multiply, divide
- Three-shaking test example

### 1.0.0-alpha.1
- Initial source code copy from luma.gl v4.1-alpha branch

