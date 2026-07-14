<mxfile host="app.diagrams.net" modified="2026-07-14T00:00:00.000Z" agent="5.0" version="21.0.0" type="device">
  <diagram name="Page-1" id="c4acf3e9-1b5c-4e2a-8f7e-1a0d5a4e3b2c">
    <mxGraphModel dx="1422" dy="794" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <!-- Start -->
        <mxCell id="start" value="" style="ellipse;whiteSpace=wrap;html=1;fillColor=#000000;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="360" y="40" width="30" height="30" as="geometry" />
        </mxCell>
        <!-- Open Login Page -->
        <mxCell id="action1" value="Open Login Page" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="310" y="110" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edge1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="start" target="action1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- Enter Email & Password -->
        <mxCell id="action2" value="Enter Email &amp; Password" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="310" y="200" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edge2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="action1" target="action2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- Click Login -->
        <mxCell id="action3" value="Click Login" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="310" y="290" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edge3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="action2" target="action3">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- Validate Credentials -->
        <mxCell id="action4" value="Validate Credentials" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="310" y="380" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edge4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="action3" target="action4">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- Decision -->
        <mxCell id="decision" value="Credentials Valid?" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="325" y="470" width="100" height="80" as="geometry" />
        </mxCell>
        <mxCell id="edge5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="action4" target="decision">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- Yes branch - Create Session -->
        <mxCell id="yes1" value="Create Session" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="550" y="485" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edgeYes" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="decision" target="yes1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="lblYes" value="Yes" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="edgeYes">
          <mxGeometry x="-0.2" y="2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <!-- Redirect to Dashboard -->
        <mxCell id="yes2" value="Redirect to Dashboard" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="550" y="575" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edgeYes2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="yes1" target="yes2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- End (Yes) -->
        <mxCell id="endYes" value="End" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#000000;strokeColor=#000000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="550" y="665" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edgeEndYes" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="yes2" target="endYes">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- No branch - Display Error -->
        <mxCell id="no1" value="Display Error Message" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="180" y="485" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edgeNo" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="decision" target="no1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="lblNo" value="No" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="edgeNo">
          <mxGeometry x="-0.2" y="2" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <!-- Return to Login -->
        <mxCell id="no2" value="Return to Login" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="180" y="575" width="130" height="50" as="geometry" />
        </mxCell>
        <mxCell id="edgeNo2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="no1" target="no2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <!-- Loop back to Enter Email & Password -->
        <mxCell id="loop" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="no2" target="action2">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="100" y="600" />
              <mxPoint x="100" y="225" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
