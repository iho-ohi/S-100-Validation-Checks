# S-100-Validation-Checks
S-100 Github repository for Validation Check development.

USE SPREADSHEET UNDER DOCUMENTS

## S-100 Validation Tests - DRAFT. Last updated 26/02/24.



|Dev ID|Check ID|Description|Classif ication|S-100 Part|S-100 Clause|Introduced|Modified|Dev use-uploaded date|
|-------|-------|----------------------------------------------------------------|-------|-------|-------|-------|-------|-------|
|	S100_Dev0001	|		|	The basic data type must be one of the supported category types.	|		|	1	|	4.5	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0002	|		|	The Derived Type must be one of the types defined in S-100 or in the Product Specification	|		|	1	|	4.6	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0003	|		|	The Enumeration Type must be part of the valid identifiers in the Enumerated Type Declaration	|		|	1	|	4.7	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0004	|		|	The Codelist Type declaration must be one of the types defined 	|		|	1	|	4.8	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0005	|		|	A Product Specification for the dataset has been registered in the IHO GI Registry	|		|	2	|	4.2.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0006	|		|	The features in the Feature Catalogue must be registered in the Concept Register and Data Dictionary Register	|		|	2	|	4.2.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0007	|		|	The producer code is registered in the Producer Code Register	|		|	2	|		|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0008	|		|	The Portrayal Catalogue is registered in the Registry, if required for the product	|		|	2	|		|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0009	|		|	The Feature Catalogue conforms to the Registry	|		|	2	|		|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0010	|		|	The Dataset conforms to the Feature Catalogue	|		|	2	|		|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0011	|		|	All class names must be defined by a bi-alpha prefix that identifies the package to which a class belongs from the defined list	|		|	4b	|	3.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0065	|		|	A Feature Catalogue shall be defined for each Product Specification 	|		|	5	|	1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0066	|		|	Definitions of features and attributes are drawn from a Feature Concept Dictionary	|		|	5	|	4.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0067	|		|	A Feature Catalogue shall be available in electronic form for any set of geographic data that contains features	|		|	5	|	4.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0068	|		|	Feature catalogue is based on the ISO 19110 standard with extensions to features types (information types and complex attributes) 	|		|	5	|	4.2.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0069	|		|	A feature type cannot be derived from an information type or vice versa	|		|	5	|	4.2.2.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0070	|		|	Each type cannot be derived from more than one super-type	|		|	5	|	4.2.2.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0071	|		|	Attributes cannot be shared between different instances	|		|	5	|	4.2.3.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0072	|		|	All simple attribute values are value types from the list in Part 2a-4.2.9	|		|	5	|	4.2.3.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0073	|		|	Each association has exactly two roles, either or both may be default	|		|	5	|	4.2.3.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0074	|		|	The documentation of Application Schemas must specify the role used for default names.	|		|	5	|	4.2.3.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0075	|		|	Each role shall have an unambiguous name.	|		|	5	|	4.2.3.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0076	|		|	Each Feature Association uses two roles that define the directed use of the relationship.  Either or both may be default.	|		|	5	|	4.2.4	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0077	|		|	The Feature Catalogue shall include definitions and descriptions of all feature and information types contain in the data, including any feature attributes and feature associations contained in the data that are associated with each feature type.	|		|	5	|	4.2.7	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0012	|		|	S-100_IO_IdentifiedObject is present and valid	|		|	6	|		|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0013	|		|	A single CRS is one of the supported single CRSs listed	|		|	6	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0014	|		|	A compound CRS must be a combination of at least two or more single CRSs 	|		|	5	|	4.3.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0015	|		|	Nesting of compound CRSs is not permitted, all components must be single CRSs	|		|	6	|	4.3.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0016	|		|	The Coordinate System Class is one of the defined coordinate systems 	|		|	6	|	4.4	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0017	|		|	The Datum is a one of the described datums 	|		|	6	|	4.5	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0018	|		|	The Coordinate Operation has a source CRS and a target CRS	|		|	6	|	4.6	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0019	|		|	The Coordinate Operations is one of the defined operation types	|		|	6	|	4.6	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0078	|		|	The associated SC_CRS must be linked at the GM_Aggregate level and not directly to a DirectPosition	|		|	7	|	4.1.2.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0079	|		|	The use of the indirect position (GM_PointRef) is not permitted	|		|	7	|	4.1.3.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0080	|		|	The types of interpolation is one of the types defined in S-100	|		|	7	|	4.2.1.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0081	|		|	The blendedParabolic interpolation should not be used where the precise location of the resultant curve is important	|		|	7	|	4.2.2.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0082	|		|	GM_SurfaceInteroplation  uses either none or planar interpolation	|		|	7	|	4.2.3.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0083	|		|	CM_Surface Patch uses a single interpolation to define the shape and position of the associated GM_Surface primitives	|		|	7	|	4.2.4.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0084	|		|	A GM_Polygon uses planar interpolation	|		|	7	|	4.2.5.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0085	|		|	A GM_Curve is composed of one or more curve segments	|		|	7	|	4.2.6.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0086	|		|	The GM_Curve segments are connected to one another, with the end point of each segment, except the last, being the start point of the next segment in the segment list.	|		|	7	|	4.2.6.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0087	|		|	Individual Product Specifications may constrain the interpolation types allowed for spatial attributes	|		|	7	|	4.2.6.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0088	|		|	GM_Primitives are part of at least one GM_Aggregate	|		|	7	|	4.2.11.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0089	|		|	All GM_Primitive contained within a GM_Aggregate use the same SC_CRS 	|		|	7	|	4.2.11.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0090	|		|	A GM_Ring must not intersect with itself	|		|	7	|	4.2.12.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0091	|		|	A GM_Surface must be subtyped as a GM_Polygon	|		|	7	|	4.2.13.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0092	|		|	A GM_SurfaceBoundary consists of references to a combination of at least one exterior GM_Ring and zero or more interior GM_Rings	|		|	7	|	4.2.14.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0093	|		|	GM_Rings must be closed as described in ISO 19107 clause 6.6.11.1	|		|	7	|	4.2.14.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0094	|		|	A GM_Point can only contain one point	|		|	7	|	4.2.16.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0095	|		|	A composite curve is a sequence of GM_OrientableCurve, each curve (except the first) begins where the previous curve ends	|		|	7	|	4.2.17.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0096	|		|	A GM_MultiPoint only contains points	|		|	7	|	4.2.19.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0097	|		|	An S100_ArcByCenterPoint start angle must be in degrees and is limited to the range [0.0, 360.0]	|		|	7	|	4.2.20.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0098	|		|	An S100_ArcByCenterPoint angular distance must be in degrees and is limited to the range [-360.0, +360.0]	|		|	7	|	4.2.20.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0099	|		|	For S100_ArcByCenterPoint the upper bound on a radius shall be less than the minimum geodesic distance from the position of the centre to its antipodal point.	|		|	7	|	4.2.20.1	|	5.1.0	|		|	20-09-2023	|
|		|		|		|		|		|		|		|		|		|
|	S100_Dev0100	|		|	Any product addressing imagery, gridded or coverage data shall pass the requirements described in the abstract test suite, presented in Appendix 8-A	|		|	8	|	8-2.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0101	|		|	The Application Schema defines one or more geographic feature types 	|		|	8	|	8-4.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0102	|		|	If a feature structure is associated with an image it is necessary to link feature IDs to individual pixels in the image	|		|	8	|	8-4.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0103	|		|	Imagery, gridded or coverage data conforms to the required Image and Gridded data Structure in Part 8, Figures 8-3 & 8-4	|		|	8	|	8-4.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0104	|		|	If imagery, gridded or coverage data metadata are encoded as features types, the Application Schema should define feature or information types defining the attributes and, for  types, a spatial representation which must be one of the spatial types defined in Part 8.	|		|	8	|	8-4.3-1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0105	|		|	For coverage encoding format, Hierarchical Data Format (HDF version 5) is used.	|		|	8	|	8-4.3-2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0106	|		|	Point sets and other sets of non-continuous geometric objects do not form tessellations	|		|	8	|	8-5.1.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0107	|		|	Geometric objects (Subtypes of the UML class GM_Object) to be used conform to the definition in ISO 19107	|		|	8	|	8-5.1.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0108	|		|	Subtypes of GM_Object used for description of spatiotemporal domains conform to the definition in ISO 19123	|		|	8	|	8-5.1.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0109	|		|	A coverage is only a grid, TIN or point set	|		|	8	|	8-5.1.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0110	|		|	A discrete coverage is a discrete or step function, not a continuous coverage	|		|	8	|	8-5.1.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0111	|		|	For each point set the position of the point, any associated attribute value and associated feature reference are known	|		|	8	|	8-5.2.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0112	|		|	A Point Set Coverage is a coverage function associated with point value pairs in 2 dimensions	|		|	8	|	8-5.2.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0113	|		|	A grid contains two or more grid lines	|		|	8	|	8-5.2.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0114	|		|	A grid covers the entire bounded space	|		|	8	|	8-5.2.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0115	|		|	A grid follows an implicit sequence or traversal order.  Traversal orders conform to those defined in Annex D of ISO 19123.	|		|	8	|	8-5.2.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0116	|		|	A tiled grid contains two or more grid tessellations for one set of data	|		|	8	|	8-5.2.4	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0117	|		|	If the cell size varies in a grid; the grid tessellation must still cover the bounded area, the traversal method must be able to sequence the cells in an order and information that describes the size of each cell must be included with the cell	|		|	8	|	8-5.2.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0118	|		|	In a grid of variable cell size nothing is stored for cells with no data	|		|	8	|	8-5.2.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0119	|		|	Grids exist in 2 or 3 dimensions	|		|	8	|	8-5.2.6	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0120	|		|	CV_TINCoverage class conforms to ISO 19123	|		|	8	|	8-5.2.8	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0121	|		|	TIN coverages are continuous coverages	|		|	8	|	8-5.2.8	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0122	|		|	Grid cell structure conforms to Section 8.2.2 of ISO 19123.	|		|	8	|	8-5.2.8	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0123	|		|	The sample space corresponding to each grid point is a cell centred at the grid point	|		|	8	|	8-5.2.8	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0124	|		|	A dataset contains a collection of one or more coverages together with associated metadata	|		|	8	|	8-5.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0125	|		|	More detailed metadata at a lower level overrides general metadata for an entire coverage or collection.	|		|	8	|	8-5.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0126	|		|	The S100_DatasetDiscoveryMetadata module conforms to S-100 Part 17	|		|	8	|	8-5.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0127	|		|	The S100_IF_CollectionMetadata module refers to the S100_IF_StructureMetadata module, the S100_IF_AcquisitionMetadata module and the S100_IF_QualityMetadata modules as sub-components	|		|	8	|	8-5.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0128	|		|	The content of a dataset is defined by the Product Specification for that particular type of data	|		|	8	|	8-5.3.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0129	|		|	A Product Specification for a particular data type needs to have a plan that indicates the organisation of that data product	|		|	8	|	8-5.3.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0130	|		|	S100_DatasetDiscoveryMetadata conforms with S-100 Part 17	|		|	8	|	8-5.3.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0131	|		|	No transmittal metadata is shown except for the information contained in the S100_DatasetDiscoveryMetadata module	|		|	8	|	8-5.3.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0132	|		|	The S100_IF_StructureMetadata module, the S100_IF_AcquisitionMetadata module and the S100_IF_QualityMetadata conform to ISO 19115-1, ISO 19115-2 and ISO 19157	|		|	8	|	8-5.3.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0133	|		|	Only one tiling scheme can be defined for a particular data collection	|		|	8	|	08-jun	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0134	|		|	The tiling scheme is discrete coverage	|		|	8	|	08-jun	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0135	|		|	Any tiling scheme used must agree  with the scheme described in the associated Product Specification  including dimensions, locations and data density of tiles as well as a tile identification mechanism (tileID)	|		|	8	|	08-jun	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0136	|		|	A CV_GeometryValuePair consists of a domain object and a record of feature attribute values	|		|	8	|	8-7.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0137	|		|	Only the subclasses CV_PointValuePair and CV_GridPointValuePair are used	|		|	8	|	8-7.2	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0138	|		|	Acceptable CV_CommonPointRule values are 'all', 'average', 'high' or 'low'	|		|	8	|	8-7.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0139	|		|	The interpolationType is a value from the codelist CV_InteroplationMethod	|		|	8	|	8-7.4	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0140	|		|	For S100_IF_GridCoverage the grid organisation is either the simple quadrilateral grid with equal cell sizes traversed by a linear sequence rule, or the variable cell size quadrilateral grid traversed by a Morton Order sequence rule. 	|		|	8	|	8-7.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0141	|		|	For S100_IF_GridCoverage the only allowable interoplationType are Bilinear interpolation, Bicubic interpolation, Nearest-neighbour and Biquadratic interpolation.	|		|	8	|	8-7.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0142	|		|	The CV_GridCoordinate  ordering shall be the same as hat of the elements of axisNames	|		|	8	|	8-7.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0143	|		|	The value of a single coordinate shall be the number of offsets from the origin of the grid in the direction of a specific axis	|		|	8	|	8-7.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0144	|		|	S100_IF_GridValues Attribute value must conform to the RecordType specified by the rangeType attribute.  If the value of an attribute is missing or unknown, a fill value must be used in its place	|		|	8	|	8-7.5	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0145	|		|	The S100_IF_Grid model is either Rectified or Georferenceable	|		|	8	|	8-7.6	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0146	|		|	Georeferenceable grids use Direct Positions of the grid points encoded along with the value record for each grid point.	|		|	8	|	8-7.6	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0147	|		|	For CV_CommonPointRule enumeration the use of 'start' and 'end' is prohibited	|		|	8	|	8-7.7.1	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0148	|		|	For S100_CV_InterpolationMethod the use of literals linear, quadratic and cubic are prohibited	|		|	8	|	8-7.7.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0149	|		|	For S100_CV_InterpolationMethod the use of lostarea method is prohibited	|		|	8	|	8-7.7.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0150	|		|	For S100_CV_InterpolationMethod, Interpolation parameters, if used, must be encoded in the interpolationParameters	|		|	8	|	8-7.7.3	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0151	|		|	The metadata for S-100 Imagery and Gridded Data conforms to Appendix 8-D	|		|	8	|	08-sep	|	5.1.0	|		|	20-09-2023	|
|	S100_Dev0152	|		|	The quality measures for imagery, gridded and coverage data conform to Appendix 8-C	|		|	8	|	08-okt	|	5.1.0	|		|	20-09-2023	|
|		|		|		|		|		|		|		|		|		|
|	S100_Dev317	|		|	HDF5 constructs requiring the use of an HDF5 library later than version 1.8.8 must not be used.	|		|	10c	|	10c-3 and 10c-5.3	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev318	|		|	At least one object, the root group, is present within the HDF5 file.	|		|	10c	|	10c-5.1.1	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev319	|		|	Within a single HDF5 file, all HDF5 objects are uniquely defined.	|		|	10c	|	10c-5.1.1	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev320	|		|	The root group may not be a member of another group.	|		|	10c	|	10c-5.1.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev321	|		|	Each named object has at least one link to it.	|		|	10c	|	10c-5.1.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev322	|		|	HDF5 data classes not listed in table 10c-1 shall not be used.	|		|	10c	|	10c-7	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev323	|		|	Values of HDF5 datatypes must conform to the constraints defined by table 10c-1.	|		|	10c	|	10c-7	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev324	|		|	"Names of HDF5 elements that encode data elements in the Application
Schema must conform to the names in the Application Schema (equivalently, the Feature Catalogue), including conformance to letter case."	|		|	10c	|	10c-8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev325	|		|	"Names of HDF5 elements that encode data elements in the Application
Schema must be in camel case."	|		|	10c	|	10c-8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev326	|		|	"Elements in embedded (“carrier”) metadata and positioning information which correspond to attributes
in Parts 4a-4c must also conform to the corresponding camel case names in Parts 4a-4c & 8."	|		|	10c	|	10c-8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev327	|		|	Names in non-embedded metadata and catalogue files in exchange sets must conform to the standard S-100 metadata and exchange catalogue schemas.	|		|	10c	|	10c-8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev328	|		|	A HDF5 file must conform to the general structure of an S-100 HDF5 file.	|		|	10c	|	10c-9.1	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev329	|		|	"If vector meta-features are present, a reference to the separate file must be
included in carrier metadata by naming the file in the metaFeatures attribute."	|		|	10c	|	10c-9.2.3	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev330	|		|	For irregular grids, the sequence of cell location arrays must conform to the sequencingRule metadata attribute in the feature container group.	|		|	10c	|	10c-9.3 and 10c-9.6	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev331	|		|	"For irregular grids, if the optional tile index component is used,
the tile index component must be named ‘tileIndex’ and be of ‘integer’ datatype."	|		|	10c	|	10c-9.3	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev332	|		|	The name of each data group is of the form 'Group_nnn'.	|		|	10c	|	10c-9.3	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev333	|		|	A maximum of 999 data groups are allowed.	|		|	10c	|	10c-9.3	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev334	|		|	The root group must be structured as described in table 10c-5.	|		|	10c	|	10c-9.4	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev335	|		|	The embedded carrier metadata in the root group shall only contain the elements listed in table 10c-6 and those allowed by the product specification.	|		|	10c	|	10c-9.4	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev336	|		|	"Only the following user defined coordinate reference systems are supported:
 - Geodetic CS (Latitude, Longitude) – Degrees; and
 - Cartesian CS (Northing, Easting or Easting, Northing) – Metres."	|		|	10c	|	10c-9.4	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev337	|		|	For the horizontal Datum all EPSG predefined Datum are allowed or any combination of predefined Prime Meridians or predefined Spheroids.	|		|	10c	|	10c-9.4	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev338	|		|	The projection methods are limited to those given in Table 10c-24.	|		|	10c	|	10c-9.4	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev339	|		|	If the horizontal CRS is defined by the EPSG code, the defined CRS should not use any other elements than the one allowed for user defined CRSs.	|		|	10c	|	10c-9.4	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev340	|		|	The Feature Information Group must be structured as described in table 10c-8.	|		|	10c	|	10c-9.5	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev341	|		|	Check that all numeric values represented as strings within the Feature Information Group are valid numbers or empty (0-length) strings.	|		|	10c	|	10c-9.5	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev342	|		|	An entry in Group_F is required for every feature type that is used in the HDF5 data file.	|		|	10c	|	10c-9.5	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev343	|		|	"Each feature description dataset must list all the attributes of the feature type (both direct and
inherited) as specified in the Feature Catalogue."	|		|	10c	|	10c-9.5	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev344	|		|	Each Feature Container Group must be structured as described in table 10c-9.	|		|	10c	|	10c-9.6	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev345	|		|	The metadata in the Feature Container Group  shall only contain the elements listed in table 10c-10 and those allowed by the product specification.	|		|	10c	|	10c-9.6	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev346	|		|	The "id" column of the Feature Attribute Table contains values that are greater than 0.	|		|	10c	|	10c-9.6.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev347	|		|	"The ""id"" column of the Feature Attribute Table always contains a value from the ""values-record"" of the Data Values
Groups of the Feature Instance Groups."	|		|	10c	|	10c-9.6.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev348	|		|	The number of additional columns of the Feature Attribute Table is greater than 0.	|		|	10c	|	10c-9.6.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev349	|		|	The additional columns of the Feature Attribute Table are based on the attributes of the feature type.	|		|	10c	|	10c-9.6.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev350	|		|	The additional columns of the Feature Attribute Table can only encode simple data type. Complex data type are separated by a dot up to the simple data type; for example, surveyDateRange.dateEnd and surveyDateRange.dateStart.	|		|	10c	|	10c-9.6.2	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev351	|		|	Each Feature Instance Group must be structured as described in table 10c-11.	|		|	10c	|	10c-9.7	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev352	|		|	A specific feature instance within the the Feature Instance Group shall only contain those attributes listed in table 10c-12 and section 10c-9.7.1 (Overriding attributes) and those allowed by the Product Specification.	|		|	10c	|	10c-9.7	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev353	|		|	If the Tiling Information Group is present, then the data must be encoded in more than one tile.	|		|	10c	|	10c-9.8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev354	|		|	The spatial union of tile surfaces must cover all the features in the S-100 dataset.	|		|	10c	|	10c-9.8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev355	|		|	The Tiling Information Group must be structured as described in table 10c-13.	|		|	10c	|	10c-9.8	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev356	|		|	The Indexes Group must be structured as described in table 10c-14.	|		|	10c	|	10c-9.9	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev357	|		|	The Positioning Group contains no attributes.	|		|	10c	|	10c-9.10	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev358	|		|	"The Positioning Group contains a coordinates dataset, which is an array of compound type with
components named the same as the axisNames dataset in the Feature Container Group."	|		|	10c	|	10c-9.10	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev359	|		|	The Positioning Group is only used for values of dataCodingFormat of 1, 3, 4, 7 and 8.	|		|	10c	|	10c-9.10	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev360	|		|	The Positioning Group must be structured as described in table 10c-16.	|		|	10c	|	10c-9.10	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev361	|		|	The values and dataset types for different data encoding formats of the Positioning Group must be as described in table 10c-17.	|		|	10c	|	10c-9.11	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev362	|		|	A Data Values Group must be structured as described in table 10c-18.	|		|	10c	|	10c-9.11	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev363	|		|	Time series data for all except the moving platforms and fixed station (stationwise) format (dataCodingFormat = 4, 8) are encoded in successive groups contained within the instance group.	|		|	10c	|	10c-9.11	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev364	|		|	The Data Values Groups are numbered sequentially 001, 002, etc, up to the maximum number of Groups.	|		|	10c	|	10c-9.11	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev365	|		|	The number of Data Values Groups must be equal to the value of metadata variable numGRP.	|		|	10c	|	10c-9.11	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev366	|		|	The attributes for a Data Values Group shall only contain those attributes defined by table 10c-19 and those allowed by the Product Specification.	|		|	10c	|	10c-9.11	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev367	|		|	When a grid cell contains a value that identifies a particular feature, the feature identifcation value must reference a row in the Feature Attribute Table.	|		|	10c	|	10c-9.11.1	|	5.1.0	|		|	26-02-2024	|
|	S100_Dev368	|		|	Where vector spatial objects residing within an external file are reference, it must be done by a string of the format: extObjRef:<fileName>:<recordIdentifier>.	|		|	10c	|	10c-13	|	5.1.0	|		|	26-02-2024	|
|		|		|		|		|		|		|		|		|		|
|	S100_Dev0020	|		|	XML catalogues conform to the S-100 Metadata Profile Schemes	|		|	17	|	2.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0021	|		|	S-100 Exchange set contains a conforming S-100_ExchangeCatalogue	|		|	17	|	4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0022	|		|	S-100 Exchange set must contain an Exchange Set Catalogue, CATALOG.XML and its digital signature CATALOG.SIGN	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0023	|		|	S-100 Exchange set content is placed inside a top level S100_ROOT folder	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0024	|		|	The S-100_ROOT folder must contain a product subfolder for each specific S-100 Product Specification data type included in the Exchange Set, as defined in the Product Specification Register of IHO Geospatial Information Registry	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0025	|		|	Each product subfolder must contain subfolders for the component dataset files (DATASSET_FILES), support files (SUPPORT_FILES) and Catalogues (CATALOGUES) as required	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0026	|		|	The ISOMetadataFile, if used, must be located in the SUPPORT_FILES folder	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0027	|		|	The ISOMetadataFile, if used, must have unique names	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0028	|		|	The name of the XML Metadata file should not be used to describe the physical content of the file	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0029	|		|	The XML Metadata file must be named MD_<data file base name>.XML	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0030	|		|	The Exchange Set Catalogue XML document instance must be named CATALOG.XML	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0031	|		|	The Exchange Set Catalogue XML (CATALOG.XML) must be located in the S100_ROOT folder with its digital signature (CATALOG.SIGN) file	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0032	|		|	All other digital signature, other than CATALOG:SIGN must be included within their corresponding resource metadata records in the CATALOG.XML	|		|	17	|	4.2	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0033	|		|	"All resources within an S-100 Exchange Set must be digitally signed and their signatures included in the Exchange Set Catalogue.
Or The S-100_DatasetDiscoveryMetadata attribute digitalSignatureValue is mandatory"	|		|	17	|	4.2 & 4.5	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0034	|		|	The format of supporting resources is valid as defined by the S100_SupportFileFormat enumeration in the Exchange Catalogue Schema	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0035	|		|	Datasets hold a reference to an External Resource as an attribute value	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0036	|		|	External resources that are physical files are located within <S-100 Product/SUPPORT_FILES subdirectory in the Exchange Catalogue file structure	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0037	|		|	All content relating to external resources must be consistent with the dataset content to form a  valid S-100 Exchange Set	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0038	|		|	External resources that are physical files are located within <S-100 Product/SUPPORT_FILES subdirectory in the Exchange Catalogue file structure	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0039	|		|	Datasets references to external resource with a URI primitive type,  must use S-100 URI form and be uniquely resolvable without requiring supplementary information within the Exchange Catalogue metadata entries	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0040	|		|	All base dataset filenames must be unique	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0041	|		|	All datasets shall follow the naming convention XXXYYYYØØØØØØØØØ.EXT, where XXX = product code, YYYY = producer code according to the Producer Code Register, ØØØØ is an arbitrary length unique code in alphanumeric characters including any differentiating characters as required, EXT is the file encoding specific file extension	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0042	|		|	The ØØØØ unique code of an arbitrary length unique code must be unique for the data producer and shall not be reused	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0043	|		|	The content in the latest revision of supporting resources is specific to the unique code used.  	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0044	|		|	A supporting resource must not be shared across product specifications	|		|	17	|	4.3	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0045	|		|	A dataset update number must be increased by one for subsequent update, until a New Edition is released	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0046	|		|	A re-issue of a dataset must have the update number of the last update applied to the dataset, and use the same Edition number	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0047	|		|	The dataset Issue data must be greater than the previous issue date of the dataset	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0048	|		|	To cancel a Base dataset file the Edition number must be set to 0	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0049	|		|	Where a dataset is cancelled and its name is reused at a later date, the issue date must be greater than the issue date of the cancelled dataset	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0050	|		|	When a datasets is cancelled it must be removed from the system	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0051	|		|	When an exchange set contains Base dataset files and update dataset files for the same datasets, then the update dataset files must follow on in the correct sequential order from the last update applied to the Base dataset file	|		|	17	|	4.4.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0052	|		|	The S100_Datacoverage attribute boundingPolygon instance is mandatory and there can only one instance	|		|	17	|	4.5	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0053	|		|	Only one defaultLocale is permitted within S100_Exchange Catalogue	|		|	17	|	4.7	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0054	|		|	Within S100_Exchange Catalogue the id attribute PT_Locale must be unique	|		|	17	|	4.7	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0055	|		|	If userDefinedMaintenanceFrequency is populated the lexical representation for duration is the ISO 8601 extended format PnYnMnDTnHnMnS	|		|	17	|	4.9	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0056	|		|	If userDefinedMaintenanceFrequency duration nS (number of seconds) is populated at least one digit must follow the decimal point if it appears	|		|	17	|	4.9	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0057	|		|	If userDefinedMaintenanceFrequency duration  is populated, reduced precision and truncated representations are permitted as long as at least one number and its designator is present	|		|	17	|	4.9	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0058	|		|	If userDefinedMaintenanceFrequency duration  is populated, reduced precision and truncated representations are permitted as long the designator 'T' is absent if and only if all the time items are absent	|		|	17	|	4.9	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0059	|		|	If userDefinedMaintenanceFrequency duration  is populated, reduced precision and truncated representations are permitted as long the designator 'P' is always present	|		|	17	|	4.9	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0060	|		|	Zero or negative values of duration are prohibited in userDefinedMaintenanceFrequency	|		|	17	|	4.9.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0061	|		|	The start and end instants of the interval calculated by combining userDefinedMaintenanceFrequency with the issue date/time must be interpreted according to Part 3 Clause 3-8	|		|	17	|	4.9.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0062	|		|	Smaller date time components of start and end instants must not be encoded unless the available of the successor dataset is know to the corresponding precision 	|		|	17	|	4.9.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0063	|		|	Zero components must only be encoded if they are significant for indicating the granularity of the start/end instants of the interval	|		|	17	|	4.9.1	|	5.1.0	|		|	07-07-2023	|
|	S100_Dev0064	|		|	If both userDefinedMaintenanceFrequency and the maintenanceDate are encoded in the same discovery metadata block, the maintenanceDate supersede the userDefinedMaintenanceFrequency	|		|	17	|	4.9.1	|	5.1.0	|		|	07-07-2023	|


